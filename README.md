# Common PIN Analysis from haveibeenpwned.com

This project involves gathering data from [haveibeenpwned.com](https://haveibeenpwned.com) for all possible PIN codes. We created an ordered wordlist based on the popularity of these PIN codes and provided visualizations to identify patterns.


## Popular PIN Codes

### 3-Digit PINs

Below is a list of the most popular 3-digit PIN codes:

`123`, `666`, `111`, `100`, `000`, `777`, `321`, `555`, `333`, `456`

[Download 3-digit PIN wordlist](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/Word%20Lists/3%20PIN%20by%20Slon104.txt)

### 4-Digit PINs

Below is a list of the most popular 4-digit PIN codes:

`1234`, `1111`, `0000`, `1342`, `1212`, `2222`, `4444`, `1122`, `1986`, `2020`

[Download 4-digit PIN wordlist](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/Word%20Lists/4%20PIN%20by%20Slon104.txt)

### 6-Digit PINs

Below is a list of the most popular 6-digit PIN codes:

`123456`, `111111`, `123123`, `000000`, `123321`, `654321`, `666666`, `121212`, `112233`, `555555`

[Download 6-digit PIN wordlist](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/Word%20Lists/6%20PIN%20by%20Slon104.txt)

### Legacy 2012

Below is a list of the most popular PIN codes from the 2012 legacy data:

`1234`, `1111`, `0000`, `1212`, `7777`, `1004`, `2000`, `2222`, `4444`, `6969`

[Download Legacy 2012 4-digit PIN wordlist](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/Legacy%202012%20Credit%20Card%20Pin%20Numbers%20leak/4%20digit%20wordlist%20old.txt)

## Visualizations

### Heatmap Analysis of 4-Digit PIN Codes

#### 1. Power Transformed Heatmap

![Heatmap of 4-digit Codes (Power Transformed, p 0.3)](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/4-digit%20%20Visualization/Heatmap%20of%204-digit%20Codes%20(Power%20Transformed,%20p%200.3).png?raw=true)

This power transformation heatmap highlights that people tend to choose PINs that are significant to them, such as a year or a combination of a date and month. The most popular PIN, `1234`, is shown in white, with several other notable outliers.

#### 2. Logarithmic Transformed Heatmap

![Heatmap of 4-digit Codes (Log Transformed)](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/4-digit%20%20Visualization/Heatmap%20of%204-digit%20Codes%20(Log%20Transformed).png?raw=true)

This logarithmic transformation heatmap provides better detail into the patterns of PIN usage. It is interesting to note that if the PIN starts with `0`, it is quite rare for the last two digits to exceed `30` or so, indicating somthing.

### Heatmap Analysis of 6-Digit PIN Codes

#### 1. Power Transformed Heatmap

![Heatmap of 6-digit Codes (Power Transformed, p 0.3)](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/6-digit%20%20Visualization/Heatmap%20of%206-digit%20Codes%20(Power%20Transformed,%20p%200.3).png?raw=true)

The power-transformed heatmap for 6-digit PINs reveals that these codes are more spread out compared to 4-digit PINs. However, there are strong patterns for the first digits, particularly those starting from `000` up to around `400`.

#### 2. Logarithmic Transformed Heatmap

![Heatmap of 6-digit Codes (Log Transformed)](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/6-digit%20%20Visualization/Heatmap%20of%206-digit%20Codes%20(Log%20Transformed).png?raw=true)

The logarithmic transformation heatmap shows a clear trend where most people avoid starting their 6-digit PINs with `0`. When a PIN does start with `0`, it often follows a date, month, or year pattern for memorable number sequences.

### 3D Visualizations of 6-Digit PIN Codes

#### 1. ABCDEF View

![3D Visualization of 6-digit Codes [ABCDEF] (Power Transformed, p 0.2)](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/6-digit%20%20Visualization%203D/3D%20Visualization%20of%206-digit%20Codes%20%5BABCDEF%5D%20(Power%20Transformed,%20p%200.2).png?raw=true)

This regular 3D view (`ABCDEF`) shows that many people tend to repeat their first and last two digits. It feels like the first two and last two digits are more predictable than the middle two, and they appear very similar to patterns seen in 4-digit PINs.

#### 2. FABCDE View

![3D Visualization of 6-digit Codes [FABCDE] (Power Transformed, p 0.2)](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/6-digit%20%20Visualization%203D/3D%20Visualization%20of%206-digit%20Codes%20%5BFABCDE%5D%20(Power%20Transformed,%20p%200.2).png?raw=true)

This view (`FABCDE`) shifts the pins to the right to better visualize patterns in odd-numbered pairs.

#### 3. ADBECF View

![3D Visualization of 6-digit Codes [ADBECF] (Power Transformed, p 0.2)](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/6-digit%20%20Visualization%203D/3D%20Visualization%20of%206-digit%20Codes%20%5BADBECF%5D%20(Power%20Transformed,%20p%200.2).png?raw=true)

This view (`ADBECF`) is designed to explore how different pairs interact with each other in 6-digit PINs.

#### 4. AFBECD View

![3D Visualization of 6-digit Codes [AFBECD] (Power Transformed, p 0.2)](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/blob/main/6-digit%20%20Visualization%203D/3D%20Visualization%20of%206-digit%20Codes%20%5BAFBECD%5D%20(Power%20Transformed,%20p%200.2).png?raw=true)

This bonus view (`AFBECD`) provides an alternative perspective on the distribution and frequency of 6-digit PINs.


## Contributing

I welcome contributions and discussions! If you have ideas, questions, or discoveries related to this project, feel free to open an [issue](https://github.com/Slon104/Common-PIN-Analysis-from-haveibeenpwned.com/issues) to start a discussion. Whether it's about improving the analysis, adding new visualizations, or suggesting optimizations, your input is valuable!

If you would like to contribute directly to the project, you can submit a pull request based on community insights from the issues.

### How to Contribute

1. **Fork the Repository**: Click the "Fork" button on the top right of this page to create a personal copy of the repository.
2. **Clone the Fork**: Use `git clone` to clone your fork locally.
3. **Create a Branch**: Make a branch for your feature or fix using `git checkout -b branch-name`.
4. **Make Changes**: Commit your changes with clear and concise commit messages.
5. **Push to Your Fork**: Push your branch to your forked repository on GitHub.
6. **Open a Pull Request**: Submit a pull request to the original repository. Make sure to link any related issues in your PR description.

Thank you for considering contributing to this project! We look forward to your ideas and improvements.

