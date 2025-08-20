<img width="742" height="145" alt="notebook" src="https://github.com/user-attachments/assets/9029ee86-3bcc-4e7d-8342-faa8a9a64412" />


Tired of checking the legitimacy of a company before applying..?  
Not anymore!   
We help you decide whether to apply or not based on Employees' reviews.  

In this project, we are using RAPID_API's Glassdoor API to fetch reviews of a given company and analyse using NLP techniques, finally helping you make a better decision.

```
RAPID_API_KEY = "GIVE YOUR API KEY"
```
In the placeholder, give your API key and just run the following cell, give the desired company name and wait for the results.
```
company_name = input("Enter name of the company: ")
analyse(company_name)
```

### Detailed Interpretation of Outputs
- The name of the company, Company ID and the logo are also displayed to ensure correctness.
- A detailed word cloud, based on most frequently used words in all the reviews is generated.
- After various considerations, finally the model gives an advice whether to join or not.  
<img width="382" height="304" alt="image" src="https://github.com/user-attachments/assets/eeab6ea5-a3e4-4199-b32d-63b4905689ef" />  
<img width="1402" height="847" alt="image" src="https://github.com/user-attachments/assets/9f11f37b-85f3-449f-bd8f-8883b437577f" />  
<img width="493" height="94" alt="image" src="https://github.com/user-attachments/assets/2d39852c-8aa4-449a-92c2-87edbc4c8684" />  


# NOTE  
Readers should understand that the model decides whether to join a company solely based on user reviews and a few other factors as shown in the notebook. And this project is not to degrade the honor of any company.

THANK YOU
