### Captcha Solver POC with LLAVA Image Recognition

#### Overview

This repository presents a Proof of Concept (POC) for a captcha solver utilizing the LLAVA image recognition model. The POC demonstrates the potential of integrating OCR and image recognition to automatically identify and solve captchas. 

#### Benchmark Results

The captcha solver POC underwent a series of 16 tests to evaluate its performance and accuracy. The results are promising, with the solver successfully passing 9 tests. While this indicates the model's potential, it also underscores the need for further refinement to enhance its reliability and efficiency.

#### POC Workflow

1. **Captcha Detection:** Identify the captcha on the webpage.
2. **Screenshot Capture:** Take a screenshot of the identified captcha.
3. **OCR Integration:** Perform basic OCR to identify the object name within the captcha.
4. **Image Slicing:** Slice the captcha into individual cases for analysis.
5. **LLAVA Prompting:** Utilize the LLAVA model to determine if the object is present in each sliced image case.
6. **Result Analysis:** Analyze the results to solve the captcha.

#### Future Improvements

While the POC has demonstrated potential, there are areas for improvement to advance the captcha solver to a stage where it can be considered for practical use:

- **Model Accuracy:** Enhance the LLAVA model's training and algorithms to improve captcha recognition accuracy.

![1](https://github.com/th3k3y/LLaVA-Captcha-Solver-POC/assets/49789253/b4bf5aa9-a4bf-4474-a716-bc872bcd3160)

![2](https://github.com/th3k3y/LLaVA-Captcha-Solver-POC/assets/49789253/1474d73d-cd13-4fb4-bbfb-5031ec4fc723)

![3](https://github.com/th3k3y/LLaVA-Captcha-Solver-POC/assets/49789253/bd773cc2-09a6-4b7d-b5e1-449db2531997)

![4](https://github.com/th3k3y/LLaVA-Captcha-Solver-POC/assets/49789253/8f0c0ef0-f31c-4423-90be-0c7393b5e10a)



