# DSC180A-Methodology-5
## Basic Info
> Name: Yishan Cai
>
> Email: yic075@ucsd.edu
> 
> Section: A09
> 
> Mentor: Biwei Huang and Jelena Bradic

## Q2 Project Brainstorm Questions
1. **What is the most interesting topic covered in your domain this quarter?**
   One particularly interesting topic from this quarter is constraint-based causal discovery, specifically the PC algorithm (Peter-Clark algorithm). It works well with linear dependencies but struggles with nonlinear relationships, which can lead to inaccurate causal graphs. In our project, the use of nonlinear models like squared or logarithmic relationships highlights this limitation. However, extending the PC algorithm with more sophisticated independence tests, such as KCI (Kernel Conditional Independence), can improve its ability to capture nonlinearities and enhance its robustness in complex data, making it a valuable tool for causal inference in such scenarios.

2. **Describe a potential investigation you would like to pursue for your Quarter 2 Project**
   We haven't finalized the specific topic for our Q2 project yet, but we're considering investigating the factors that affect stock returns. Our focus includes both macroeconomic and microeconomic conditions, such as CPI, GDP, unemployment rate, policy interest rate, company financial health (liabilities, cash flow), market sentiment from tweets, and whether the company is newly publicly listed. However, some of these metrics, particularly those related to a company's financial condition, may be difficult to obtain. Additionally, the [tweet dataset](https://www.kaggle.com/datasets/thedevastator/tweet-sentiment-s-impact-on-stock-returns) we've found requires significant cleaning and data mining efforts.
   
3. **What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
   We applied the PC, FCI, and GES algorithms to our simulation dataset, but some of the predicted edges did not perform well. Therefore, we may need to adjust the models used to achieve better results.

4. **What other techniques would you be interested in using in your project?**
   We have currently applied the Additive Noise Model to test the independence of our features. However, it does not perform well with non-linear variables, so we are considering switching to a Gaussian Process Regressor to assess independence for variables with non-linear relationships. 
