# AWS Certified Solutions Architect – Associate (SAA-C03)

## Course Fundamentals and AWS Accounts

### Creating general(management) account

- we can use email alias to create multiple accounts in aws
  eg: user.aws+management@proton.me

- Signup for a root account

- Signin using the account email & password

- Enter alternate contacts

- Under `IAM User and Role Access to Billing Information` section check the `Activate IAM Access` option

- Use the Region as N.Virginia

- Activate MFA

  <img title="" src="assets/turn-on-mfa.png" alt="MFA" width="195">

---

### Creating Alerts to email

- Go to `Billing and Cost Management`

  <img title="" src="assets/create-budget.png" alt="MFA" width="195">

- Enable PDF invoices to email

  - Click on `Billing Preferences`
  - Click edit button on `Invoice delivery preferences` box
  - Check the `PDF invoices delivered by email` checkbox and click Update button

- Enable Free tier alerts
  - Click edit button on `Alert preferences` box
  - Select both `Receive AWS Free Tier alerts` and `Receive CloudWatch billing alerts` checkboxes

<img title="after activate both options you'll see following output" src="assets/after-activate-email-alerts.png" alt="MFA" width="80%" align="center"/>

<sup><sub> after activate both options you'll see above output </sub></sup>

---

### Creating Budget

- Go to `Billing and Cost Management`

  <img title="" src="assets/create-budget.png" alt="MFA" width="195">

- Click on `Create a Budget` button
  - Budget Setup - `Use a Template`
  - Templates - `Zero spend budget`
- Give a name and Email recipients to the Budget
- Click on `Create Budget`
