# AV-India-ML-Hiring-Hackathon-2019

<h2 id="problem-statement">Problem Statement</h2>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
<h2 id="loan-delinquency-prediction">Loan Delinquency Prediction</h2>
Loan default prediction is one of the most critical and crucial problem faced by financial institutions and organizations as it has a noteworthy effect on the profitability of these institutions. In recent years, there is a tremendous increase in the volume of non &ndash; performing loans which results in a jeopardizing effect on the growth of these institutions.&nbsp;
<p>Therefore, to maintain a healthy portfolio, the banks put stringent monitoring and evaluation measures in place to ensure timely repayment of loans by borrowers. Despite these measures, a major proportion of loans become delinquent. Delinquency occurs when a borrower misses a payment against his/her loan.</p>
<p>Given the information like mortgage details, borrowers related details and payment details, our objective is to identify the delinquency status of loans for the next month given the delinquency status for the previous 12 months (in number of months)</p>
<h2 id="data-description">Data Description</h2>
</div>
</div>
</div>
</div>
<h3 id="trainzip">train.zip</h3>
<p>train.zip contains train.csv.&nbsp;<strong>train.csv</strong>&nbsp;contains the training data with details on loan as described in the last section</p>
<h3 id="data-dictionary">Data Dictionary</h3>
<table dir="ltr" border="1" cellspacing="0" cellpadding="0"><colgroup><col width="100" /><col width="368" /></colgroup>
<tbody>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Variable&quot;}"><strong>Variable</strong></td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Description&quot;}"><strong>Description</strong></td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;loan_id&quot;}">loan_id</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Unique loan ID&quot;}">Unique loan ID</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;source&quot;}">source</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Loan origination channel&quot;}">Loan origination channel</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;financial_institution&quot;}">financial_institution</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Name of the bank&quot;}">Name of the bank</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;interest_rate&quot;}">interest_rate</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Loan interest rate&quot;}">Loan interest rate</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;unpaid_principal_bal&quot;}">unpaid_principal_bal</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Loan unpaid principal balance&quot;}">Loan unpaid principal balance</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;loan_term&quot;}">loan_term</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Loan term (in days)&quot;}">Loan term (in days)</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;origination_date&quot;}">origination_date</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Loan origination date&quot;}">Loan origination date (YYYY-MM-DD)</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;first_payment_date&quot;}">first_payment_date</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;First instalment payment date&quot;}">First instalment payment date</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;loan_to_value&quot;}">loan_to_value</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Loan to value ratio&quot;}">Loan to value ratio</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;number_of_borrowers&quot;}">number_of_borrowers</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Number of borrowers&quot;}">Number of borrowers</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;debt_to_income_ratio&quot;}">debt_to_income_ratio</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Debt-to-income ratio&quot;}">Debt-to-income ratio</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;borrower_credit_score&quot;}">borrower_credit_score</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Borrower credit score&quot;}">Borrower credit score</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;loan_purpose&quot;}">loan_purpose</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Loan purpose&quot;}">Loan purpose</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;insurance_percent&quot;}">insurance_percent</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Mortgage insurance percent&quot;}">Loan Amount percent covered by insurance</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;co-borrower_credit_score&quot;}">co-borrower_credit_score</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Co-borrower credit score&quot;}">Co-borrower credit score</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;insurance_type&quot;}">insurance_type</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Mortgage insurance type&quot;}">0 - Premium paid by borrower, 1 - Premium paid by Lender</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;m1 to m12&quot;}">m1 to m12</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Month-wise loan performance (deliquency in months)&quot;}">Month-wise loan performance (deliquency in months)</td>
</tr>
<tr>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;m13&quot;}">m13</td>
<td data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;target, loan deliquency status (0 = non deliquent, 1 = deliquent)&quot;}">target, loan deliquency status (0 = non deliquent, 1 = deliquent)</td>
</tr>
</tbody>
</table>
<h3 id="testzip"><br />test.zip</h3>
<p>test.zip contains test.csv which has details of all loans for which the participants are to submit the delinquency status - 0/1 (not probability)</p>
<h3 id="sample_submissionzip">sample_submission.zip</h3>
<p>sample_submission.zip contains the submission format for the predictions against the test set. A single csv needs to be submitted as a solution.</p>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
<h2 id="evaluation-metric">Evaluation Metric</h2>
Submissions are evaluated on F1-Score between the predicted class and the observed target.</div>
<div class="column">&nbsp;</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<h2 id="public-and-private-split">Public and Private Split</h2>
Test data is further randomly divided into Public (40%) and Private (60%) data.
<ul>
<li>Your initial responses will be checked and scored on the Public data.</li>
<li>The final rankings would be based on your private score which will be published once the competition is over.</li>
</ul>
<h2 id="hackathon-rules">Hackathon Rules</h2>
<ol>
<li>Setting the final submission is mandatory. Without a final submission, the submission corresponding to best public score will be taken as final submission</li>
<li>Use of external datasets is not allowed</li>
<li>Use of loan_id variable as an input to the model is not allowed</li>
<li>You can only make 15 submissions per day</li>
<li>Code file is mandatory while setting&nbsp;final submission. For GUI based tools, please upload a zip file of snapshots of steps taken by you, else upload code file.</li>
<li>The code file uploaded should be pertaining to your final submission.</li>
<li>No submission will be accepted after the contest deadline</li>
</ol>
</div>
<p>&nbsp;</p>

# LB Score 0.34
