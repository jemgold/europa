# europa
neural network gerstner

## theory

we can encode any series of typographic combinations as a list of <img src="http://tex.la/x%20%5Cin%20%5B0%2C1%5D">.

```
dFontFamily, dFontWeight, bFontFamily, bFontWeight, bFontSize, dSizeMultiplier, dMargin, dIndent
[0, 0, 0, 0, 0, 0, 0, 0]
```

how about processing a seminal piece of typographic design like Schiff Nach Europa into paragraph-level training data - their own typographic choices, and the relationship between paragraphs?

![2211264227_116e0f96e1_o](https://cloud.githubusercontent.com/assets/591643/9155084/71c43716-3eac-11e5-903b-057e915bec3c.jpg)
![2212046928_9333a95bb1_o](https://cloud.githubusercontent.com/assets/591643/9155081/717c5414-3eac-11e5-94ff-136b865ecc97.jpg)
![2212046934_df29de8c3f_o](https://cloud.githubusercontent.com/assets/591643/9155082/718209f4-3eac-11e5-9c0b-aa49c3bef64a.jpg)
![2212046936_5508d5b67f_o](https://cloud.githubusercontent.com/assets/591643/9155083/719b62d2-3eac-11e5-9829-d5dec587b57a.jpg)
![2212046938_9bbfbef04a_o](https://cloud.githubusercontent.com/assets/591643/9155085/72149850-3eac-11e5-8aec-6e271ec6cee5.jpg)
![2212046940_43e112e12e_o](https://cloud.githubusercontent.com/assets/591643/9155086/721f813e-3eac-11e5-8e29-e2dfc764264f.jpg)

This all seems serializable; if it is we can train a neural network to design in this style. relationships between text length and font size, or line length etc.
