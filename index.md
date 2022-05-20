# Simple GitHub Pages / Doxygen test



This is a landing page and has just been written in markdown to show the following:

- This repository can be viewed as source [here](https://github.com/bit-hack/test.io).

- It can also be viewed as a page on github.io [here](https://bit-hack.github.io/test.io/).

- You can directly view the html doxygen online [here](https://bit-hack.github.io/test.io/html/index.html).

- You can link to other markdown files [here](other.md).

----

Because this is markdown code blocks still work as expected:
```c
		double cutoff = 2.0 * cutoff / sample_rate;
		double res    = 1.0;  // pow(10.0, 0.05 * -res_slider);
		double k      = 0.5 * res * sin(pi * cutoff);
		double c1     = 0.5 * (1.0 - k) / (1.0 + k);
		double c2     = (0.5 + c1) * cos(pi * cutoff);
		double c3     = (0.5 + c1 - c2) * 0.25;
```
