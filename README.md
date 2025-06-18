# Lab 5: Prompt Engineering for Social Good

---

## 📘 Introduction

This lab delves into the world of AI tokenization, a cornerstone of language models like those developed by OpenAI, with a special focus on its application for social good. By understanding how to segment text into tokens—AI's basic unit of understanding—we explore not just the mechanics but also the ethical implications of token economy. Through practical exercises, we'll discover how optimized token use can contribute to more sustainable and accessible AI solutions, driving positive change in society.


---

## 🎯 Learning Objectives

- **Understand Tokenization**: Comprehend the significance of tokenization in AI language processing and the impact of token economy on scalability and cost.
- **Apply FACTORS**: Utilize the FACTORS mnemonic to engineer precise prompts, ensuring that each component — Format, Action words, Context, Tone, Output, Role, and Specific items to avoid is optimized to guide the AI's output towards actionable insights.
- **Promote Social Good**: Integrate the principles of prompt engineering to address real-world problems, specifically focusing on the United Nations Sustainable Development Goals (SDGs), to conceptualize AI-driven solutions for societal benefit.
-**Evaluate and Refine**: Critically assess and refine prompts to reduce token usage without compromising on quality, enhancing your ability to create economically and ethically sound AI interactions.



---

## ⏱️ Estimated Time
2 hours

---

## 💵 Estimated Cost
$0.50 - $1 (View your OpenAI usage [here](https://platform.openai.com/usage))

---

## 🧰 Materials

- Your Lab2: Generating Text with OpenAI's Models  
- [Examples - OpenAI API](https://platform.openai.com/examples)
- [THE 17 GOALS| Sustainable Development](https://sdgs.un.org/goals)
- [Tokenizer - OpenAI Platform](https://platform.openai.com/tokenizer)


---


## ⚙️ 1.1 What is Prompt Engineering

1. Prompt Engineering is the new term for the process of structuring words and sentences for generative artificial intelligence models to be able to understand. It is important to have specific prompts that reflect the needs of the user in order to gain a satisfactory output from generative AI. In the following sections, we will go over some effective prompt engineering techniques and examples of prompts that can obtain satisfactory outputs from AI.

Here are some basic prompt engineering techniques **(FACTORS)**: 
1. **Format of Response**: specify the level of detail, the brevity, and overall format of the response you wish to receive. 
2. **Action Words**: use action words throughout your prompt to guide the AI’s content generation.
3. **Context**: offer background information to frame your prompt within a specific scenario/goal.
4. **Tone and Formality**: define the style and seriousness appropriate for the intended audience.
5. **Output**: provide an example output to illustrate your expectations.
6. **Role**: clarify the model’s assumed identity, profession, expertise, etc to shape its response. 
7. **Specific Items to Avoid**: Identify any content that should be excluded from the AI's responses.

---

## 🕺 Let’s Break it Down

Here is a sample prompt for a financial analysis of 2024 cryptocurrency trends:

*Prepare a brief report as a financial analyst, focusing on the cryptocurrency market trends from Q1 2024. List the top 5 investment risks and opportunities, ensuring to omit legal considerations. The response should be in a bullet-point format suitable for an investment strategy meeting. For example, you might start with 'Risk: Volatility – Cryptocurrencies have shown significant price fluctuations...'*

Let's delve deeper into this prompt’s construction to find where various prompt techniques have been utilized for a more precise response.

<table style="border-collapse: collapse; width: 100%; font-family: Arial, sans-serif;">
  <thead>
    <tr>
      <th style="text-align: left;">Prompt Text</th>
      <th style="text-align: left; border-left: 1px solid #000;">Analysis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        Prepare a brief report [1] <strong>as a financial analyst</strong>, focusing on the cryptocurrency [2] <strong>market trends from Q1 2024</strong>.
      </td>
      <td style="border-left: 1px solid #000;">
        <strong>1—Role.</strong> Position yourself as a financial analyst for a professional analysis.<br>
        <strong>2—Context.</strong> Focus on the cryptocurrency market trends for the specified quarter.<br>
      </td>
    </tr>
    <tr>
      <td>
        [3] <strong>List</strong> the top 5 investment risks and opportunities, [4] <strong>ensuring to omit legal considerations</strong>.
      </td>
      <td style="border-left: 1px solid #000;">
        <strong>3—Action Words.</strong> Utilize dynamic verbs to delineate the investment risks/opportunities clearly.
        <strong>4—Specific Items to Avoid.</strong> Omit any legal considerations from the outputted analysis.
      </td>
    </tr>
    <tr>
      <td>
        The response should be in a [5] <strong>bullet-point format</strong> [6] <strong>suitable for an investment strategy meeting</strong>.
      </td>
      <td style="border-left: 1px solid #000;">
        <strong>5—Format of Response.</strong> Opt for a bullet-point format to ensure clarity and conciseness.<br>
        <strong>6—Tone and Formality.</strong> Maintain a professional tone.
      </td>
    </tr>
    <tr>
      <td>
        [7] <strong>For example</strong>, you might start with 'Risk: Volatility – Cryptocurrencies have shown significant price fluctuations...'
      </td>
      <td style="border-left: 1px solid #000;">
        <strong>7—Example.</strong> 'Risk: Volatility – Cryptocurrencies have shown significant price fluctuations...'
      </td>
    </tr>
  </tbody>
</table>

By dissecting this prompt, we can better understand how each component contributes to creating a clear, focused, and effective request for AI-generated content. Remember, the quality of the input significantly influences the quality of the output.

Now it’s your turn! Please analyze the following prompt by identifying the prompt technique being used at each bracketed number in Table 1. Identify which of the FACTOR element(s) are used and elaborate.

Imagine you are a [1] **data analyst**. You have been given a [2] **dataset about the recent trends in renewable energy adoption across various countries**. Your [3] **task is to identify the top three countries with the highest increase in solar energy usage over the last five years**. Please present the findings in a [4] **concise bullet-point list**, using the data provided.


| [1] |
|-----|
| [2] |
| [3] |
| [4] |

Table 1. Prompt analysis Part 1

---

Here is a BAD example of prompt engineering by Bob, a student who wants to write a research paper about the pros and cons of working from home in 2024: 

*Write something about work from home*.

Please state 3 reasons why it is not the most effective prompt for the desired output in **Table 2**. 
**Reasons**:

| [1] |
|-----|
| [2] |
| [3] |

Table 2. Prompt critique

---

Using at least 3 FACTORS techniques, write a revised version of the prompt that can give the model clearer instructions and analyze the FACTORs techniques used in your revised prompt in Table 3.

Revised Prompt: 

|---|
---


Table 3. Revised prompt according to FACTOR elements

---
















