
# Analyze A/B Test Results

 We will conduct A/B testing to help an e-commerce website to understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.
 
 **Project Details:**
 
 We will work through three parts as follows:
 
**Part I - Probability**
>Compute Statistics to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

**Part II - A/B Test**

>Conduct hypothesis testing assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%. The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

**Part III - Regression**

>Perform logistic regression to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

## Conclusion

- We have conducted hypothesis testing through different statistical tests, and all of these approaches indicates that we fail to reject the null hypothesis and we cannot assume that the new page achieves higher conversion rate than the old page.

- Country has no influence on the conversion rate as the influence of landing page is not different among different countries.

- Launching the new page is unnecessary and useless as the conversion rate associated with the new page is not higher than that associated with the old page.

Thus, I recommend to the management that focusing on creating a new landing page or keeping the current page would be more benefecial than continuing on testing the suggested new page.

