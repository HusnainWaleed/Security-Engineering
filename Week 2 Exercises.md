 week 2
Task 1A

1. **"Not Secure" Cautioning in the Main Picture**:
   - Assuming I experience the "Not Secure" cautioning in the primary picture, I will be wary about visiting the site. This cautioning regularly seems when the site needs appropriate encryption, and it implies potential dangers like information interference. To relieve these dangers, I will try not to enter delicate data and reevaluate my choice to utilize the site.

2. **"Trusted" Site in the Second Picture**:
   - On the off chance that a site shows up as "trusted" in the subsequent picture, I will have good expectations about its security. This assignment recommends that the site has a substantial SSL/TLS declaration, guaranteeing scrambled associations. I would continue with utilizing the site, realizing that my information is better safeguarded against block attempt.

3. **Other Techniques to Distinguish Phishing/Trick Sites**:
   - If I have any desire to distinguish phishing or trick locales, I will:
     - Examine the URL for any grammatical mistakes or surprising characters.
     - Check the site's possession and search for contact data.
     - Use program augmentations or online instruments to really take a look at the website's standing.
     - Remain informed about normal phishing methods and digital dangers to all the more likely perceive possible dangers.

4. **Typosquatting and Its Significance to the Pictures**:
   - Assuming I go over typosquatting, I will be wary. Typosquatting includes misleading area names that exploit typographical blunders. With regards to the gave pictures, it could lead clients to fake locales that could set off the "Not Secure" cautioning because of lacking safety efforts. I will twofold really look at the URL for exactness to try not to fall into this snare.

5. **UDRP and Battling Typosquatting**:
   - Assuming I were managing typosquatting issues, I would consider utilizing the Uniform Area Name Question Goal Strategy (UDRP). UDRP permits brand name holders to challenge areas that encroach on their privileges. By recording a UDRP grievance, I might actually deal with or eliminate the encroaching space, safeguarding my image and clients.

6. **Monitoring Areas for Phishing Attempts**:
   - In the event that I possessed the space ouspg.org and worked a crypto banking application at bank.ouspg.org, I would screen different spaces to distinguish conceivable phishing endeavors. These would include:
     - Spaces with slight varieties or grammatical mistakes of my own, for example, ouspg.com or bankouspg.org.
     - Destinations that sound comparable or copy my image.
     - Spaces with various high level areas (TLDs), like .net or .co.
   - To support observing, I could utilize online apparatuses or administrations to get cautions about expected dangers, assisting me with shielding my clients from phishing tricks.



**Task 1B**

Digital certificates are used to verify the identity of a website or server. They are used in a variety of applications, including online banking, e-commerce, and secure email.

Certificates are important for online payments and banking security because they help to prevent fraud and protect customer data. For example, when you visit a bank's website, the certificate will verify that the website is actually operated by the bank and not by an impostor. This helps to prevent phishing attacks, where fraudsters create fake websites that look like real websites in order to steal customer login credentials.

Certificates also have a number of other uses, such as:

Securely transferring files over the internet
Digitally signing documents
Authenticating users to applications

TLS (Transport Layer Security) is a cryptographic protocol that provides secure communication over a computer network. It is used in a variety of applications, including online banking, e-commerce, and secure email.

TLS mitigates a number of attacks, including:
- Man-in-the-middle attacks: TLS prevents attackers from intercepting and modifying data in transit.
- Eavesdropping attacks: TLS prevents attackers from eavesdropping on data in transit.
- Impersonation attacks: TLS prevents attackers from impersonating websites or servers.

This is important for online banking because it helps to protect customer data from being stolen or tampered with.

Browsers use certificates for ensuring browsing security by verifying the identity of websites and servers. When you visit a website, your browser will check the certificate to see if it is valid and issued by a trusted certificate authority. If the certificate is valid, then your browser will establish a secure connection with the website.

The warning in the picture above means that the website's certificate is not valid. This could be because the certificate is expired, revoked, or issued by an untrusted certificate authority. It is important to be careful when visiting websites that have warnings about their certificates, as they could be unsafe.

**Certificate Authorities**

Certificate authorities (CAs) are organizations that issue digital certificates. They are responsible for verifying the identity of website owners and servers before issuing certificates.

It would be bad if a trusted certificate authority was compromised because it would allow attackers to issue fraudulent certificates. This could then be used to launch a variety of attacks, such as phishing attacks and man-in-the-middle attacks.

Certificate transparency (CT) is a system that helps to prevent CAs from issuing fraudulent certificates. CT logs are public records of all certificates that have been issued by CAs. This allows anyone to audit the certificates that have been issued and to report any fraudulent certificates.

Certificate transparency is important because it helps to ensure that certificates are only issued to legitimate website owners and servers. This helps to protect users from fraud and attacks.



**Task 2:Payment Cards**

**Questions: Payments**

1.  **Why do modern payment cards use a chip and not a magnetic stripe?**
   - Current installment cards utilize a chip since it offers upgraded security contrasted with attractive stripes. Chips produce special exchange codes for each buy, making it hard for fraudsters to clone cards. Attractive stripes, then again, store static information that can be effortlessly duplicated and utilized for unapproved exchanges.

2. **What are EMV Certificates and why are they relevant for payment protection?**
   - EMV (Europay, Mastercard, and Visa) testaments are cryptographic declarations utilized in chip-empowered installment cards to validate the card and the terminal during an exchange. They are significant for installment assurance since they assist with guaranteeing that both the card and the installment terminal are veritable, decreasing the gamble of card cloning and fake exchanges.

3. **What attacks exist against payment cards?**
   - There are a few assaults against installment cards:
     - **Card-not-present (CNP)**: These assaults happen in on the web or distant exchanges where the actual card is absent. Fraudsters might utilize taken card subtleties for unapproved buys.
     - **Contactless payment**: Aggressors can utilize gadgets to skim information from contactless cards in the event that the cards' security highlights are feeble.

**Questions: MFA**

4. **How is multi-factor authentication (MFA) used in banking?**
   - MFA in banking regularly includes utilizing at least two verification elements to confirm a client's personality. This can incorporate something the client knows (e.g., a secret word), something the client has (e.g., a savvy card or token), or something the client is (e.g., biometric information like a unique finger impression). MFA improves security by requiring various evidences of character.

5. **How does multi-factor authentication increase payment security?**
   - MFA increments installment security by adding an additional layer of assurance. It guarantees that regardless of whether a fraudster gets a client's secret key or card subtleties, they would in any case require admittance to the extra validation factor, making it more moving for unapproved exchanges to happen.

6. **What MFA methods are you using in you daily life??**
   - In my everyday existence, I could utilize different MFA strategies, for example,
     - Two-factor verification (2FA) by means of instant messages or authenticator applications for online records.
     - Biometric confirmation, similar to unique finger impression or face acknowledgment, on my cell phone.
     - Brilliant cards or tokens for getting to get frameworks at work or for web based banking.

7. **What attacks exists against different forms of 2FA?**
   - Assaults against various types of 2FA include:
     - **Time sensitive one-time passwords (TOTP)**: Assailants might catch or phish the produced codes during login.
     - **Instant message (SMS)**: SIM trading assaults, where an aggressor assumes command over a client's telephone number, can be utilized to block SMS-based 2FA codes.



**Task 3: Card Fraud- An essay explaining the card exploitation stories.**

**Development of Card Extortion: 10 years of Changing Landscapes**

Card extortion has developed fundamentally throughout the last ten years, driven by mechanical progressions, changing exchange scenes, and moving worldwide patterns. This rundown digs into the multi-layered universe of card extortion, featuring key patterns, sorts of misrepresentation, geological varieties, and the effect of innovation and guidelines somewhere in the range of 2008 and 2019.

**Sorts of Card Fraud**:

Card misrepresentation incorporates different strategies, including:

1. **Card-Present Fraud**: Includes the utilization of actual installment cards in fake exchanges, frequently through card cloning or skimming gadgets at ATMs or retail location (POS) terminals.

2. **Card-Not-Present (CNP) Fraud**: Happens in on the web or distant exchanges, where the card isn't actually present. Fraudsters utilize taken card subtleties for unapproved buys.

3. **Account Takeover (ATO)**: Includes unapproved admittance to a cardholder's record, normally through phishing assaults or qualification stuffing, permitting aggressors to make exchanges for the casualty's benefit.

4. **Card-Not-Present (CNP) Fraud**: Happens in on the web or far off exchanges, where the card isn't truly present. Fraudsters utilize taken card subtleties for unapproved buys.

**Topographical Variations**:

The commonness of card misrepresentation types differs geologically because of elements like reception of secure advances, administrative measures, and financial circumstances. Created nations frequently experience higher paces of CNP misrepresentation because of their high level internet business markets, while arising economies might confront more card-present extortion because of lower innovation reception.

**Changes in the Misrepresentation Scene (2008-2019)**:

The misrepresentation scene went through tremendous changes somewhere in the range of 2008 and 2019, driven by a few elements:

1. **Shift to EMV (Chip-and-PIN)**: Numerous nations changed to EMV (Europay, Mastercard, and Visa) chip innovation, making card-present extortion more testing as it diminished card cloning.

2. **Rise in CNP Fraud**: As EMV innovation further developed card-present security, fraudsters moved concentration to CNP misrepresentation, focusing on web-based exchanges. The comfort of web based shopping added to the increment.

3. **Mobile Installments and Contactless**: The reception of portable installment applications and contactless card innovation presented new roads for misrepresentation, including versatile application takes advantage of and contactless card skimming.

4. **Data Breaches**: High-profile information breaks uncovered immense measures of touchy cardholder information, filling account takeover and CNP extortion.

**Striking Expansion in Record Takeover (ATO)**:

Account takeover saw a prominent increment throughout the past 10 years because of the ascent in information breaks. Cybercriminals utilized taken certifications to acquire unapproved admittance to accounts, conveying it a critical intimidation to cardholders and monetary foundations.

**Effect of Innovation and Regulations**:

A few innovations and guidelines influenced card misrepresentation:

1. **EMV Adoption**: The boundless reception of EMV chip innovation made it more hard to clone cards, lessening card-present extortion.

2. **Tokenization**: Installment card tokenization improved security by supplanting card subtleties with novel tokens for exchanges, making it provoking for aggressors to think twice about information.

3. **Strong Client Confirmation (SCA)**: Guidelines like the EU's PSD2 ordered SCA for online exchanges, further reinforcing security by requiring different verification factors.

4. **Machine Learning and AI**: High level extortion location frameworks, fueled by AI and man-made reasoning, worked on the capacity to recognize fake examples.

**Changing Exchange Landscape**:

The exchange scene went through critical movements:

1. **E-business Boom**: Internet shopping flooded, prompting expanded CNP exchanges.

2. **Contactless Payments**: Contactless installments acquired prevalence, offering accommodation yet additionally presenting new extortion chances.

3. **Mobile Payments**: The expansion of versatile installment applications prompted a change in installment conduct, with additional exchanges directed through cell phones.

**Web and Web based business' Effect on Card Fraud**:

The web and online business upset shopping, making it advantageous yet in addition powerless to extortion. The namelessness and simplicity of online exchanges pulled in fraudsters. Be that as it may, secure advancements like tokenization and SCA have further developed online business security.

**Significance of Forestalling Information Breaches**:

Forestalling information breaks is urgent in diminishing card extortion. Breaks uncover cardholder information that can be utilized for different deceitful exercises, including CNP misrepresentation and ATO assaults. Carrying out strong information safety efforts is fundamental in impeding these dangers.

**Installment Card Tokenization's Role**:

Installment card tokenization plays had a crucial impact in upgrading security. By supplanting card subtleties with interesting tokens for exchanges, it decreases the gamble of cardholder information openness. Regardless of whether tokens are caught, they are pointless without the relating tokens.

In outline, the development of card extortion somewhere in the range of 2008 and 2019 was set apart by a shift from card-present to card-not-present misrepresentation, driven by mechanical headways and changing exchange ways of behaving. While EMV reception decreased card-present misrepresentation, CNP and ATO assaults turned out to be more predominant. Administrative measures, innovation developments like tokenization, and the significance of forestalling information breaks have been critical in fighting these advancing card extortion dangers.


**Task 3**

### Evolution of card fraud

**What kinds of card fraud exist?**

There are two main types of card fraud: **card-present fraud** and **card-not-present fraud**.

* **Card-present fraud** occurs when the card is physically present with the fraudster at the time of the transaction. This type of fraud can include counterfeiting, skimming, and lost or stolen cards.
* **Card-not-present fraud** occurs when the card is not physically present with the fraudster at the time of the transaction. This type of fraud can include online fraud, phone fraud, and mail order fraud.

**How does card fraud type prevalence differ geographically?**

Card-present fraud is more common in regions where cash is still the primary payment method. Card-not-present fraud is more common in regions where online and mobile payments are more popular.

**How has the fraud landscape changed between 2008-2019? Why?**

The fraud landscape has changed significantly between 2008 and 2019. Card-not-present fraud has become more common, while card-present fraud has become less common. This is due to the increasing popularity of online and mobile payments.

**What type of fraud has seen a notable increase during the last decade?**

Online fraud has seen a notable increase during the last decade. This is due to the increasing popularity of online shopping and the growing sophistication of online fraudsters.

**What technologies or regulations have had an impact on card fraud?**

A number of technologies and regulations have had an impact on card fraud. These include:

* **Chip-and-PIN technology:** Chip-and-PIN technology has made it more difficult to counterfeit and skim cards.
* **Strong customer authentication (SCA):** SCA is a regulation that requires banks to implement additional security measures for online and mobile payments. This includes measures such as two-factor authentication and one-time passwords.
* **Fraud detection systems:** Fraud detection systems use machine learning to identify and flag fraudulent transactions.

**How has the transaction landscape changed in the same period?**

The transaction landscape has changed significantly in the same period. Online and mobile payments have become more popular, while cash payments have become less common.

**What kind of transactions have become increasingly popular?**

Online and mobile payments have become increasingly popular. This is due to the convenience and flexibility of these payment methods.

**What kind of transactions have had a high risk of being fraudulent?**

Online and mobile transactions have a higher risk of being fraudulent than in-person transactions. This is because it is easier for fraudsters to impersonate legitimate customers and make unauthorized transactions online and over the phone.

**Has this changed at all during 2008-2019?**

Yes, the risk of fraud for online and mobile transactions has increased during 2008-2019. This is due to the increasing sophistication of online fraudsters.

**What effect has internet and e-commerce had on card fraud?**

The internet and e-commerce have had a significant impact on card fraud. Online fraud has become more common due to the increasing popularity of online shopping.

**Why is preventing data breaches important in preventing card fraud?**

Data breaches can expose sensitive customer information, such as card numbers and CVVs. This information can then be used by fraudsters to make unauthorized transactions.

**How does payment card tokenization help in this?**

Payment card tokenization is a process that replaces a card number with a unique token. This token can be used to make payments without revealing the actual card number. This makes it more difficult for fraudsters to use stolen card numbers.

**Other notable findings**

- In addition to the increasing prevalence of online fraud, there has also been a rise in fraud involving contactless payments. This is because contactless payments can be made without the need to enter a PIN, making them more vulnerable to fraud.
- Another notable trend is the increasing sophistication of fraudsters. Fraudsters are now using more sophisticated methods to steal card information and make unauthorized transactions. For example, they are using phishing emails and smishing text messages to trick consumers into revealing their card information. They are also using malware to infect computers and mobile devices, which can then be used to steal card information.

**How to protect yourself from card fraud**

There are a number of things that consumers can do to protect themselves from card fraud. These include:

-Be careful about where you enter your card information. Only enter your card information on secure websites.
-Use strong passwords and enable two-factor authentication for your online accounts.
-Monitor your account statements regularly and report any unauthorized transactions immediately.
-Be careful about clicking on links in emails and text messages. Phishing emails and text messages are a common way for fraudsters to steal personal information.
-Be aware of the latest fraud

**Task 5**


**Task 4 **
I spent so much time in understanding it but was able to do half of the task so not uploading the complete answers. I did not have any exoerience in inspecting the websites so it was a quite difficult task for me to do.

Subdomain TakeOver

Task A: Find out what the application does when you log in

What methods get called and where?
![image](https://github.com/husnaing147/Security-Engineering/assets/96866520/4b5f374b-b586-4387-8ad2-1ec053b8f0c4)
as seen in the picture js.js and dom.js get called in the network tab.

What data gets saved?

As it can be seen in the screenshot these data are saved.
local and session storage, indexed db, Web SQL, Cookies and cache storage
![image](https://github.com/husnaing147/Security-Engineering/assets/96866520/421b424e-13c9-4451-9da0-b0f7144114ce)


Is any data sent to external services?
No data is sent to external serviecs as per my observation.

Is there anything hazardous about the login process
Yes there comes an error and I have attached the screenshot.
![image](https://github.com/husnaing147/Security-Engineering/assets/96866520/3aae7aa0-2407-47d8-bc56-cb54298de263)



Task B: Figure out which subdomain of the application is vulnerable to takeover

How did you figure out the domain?
How can you find out the hosting provider after finding out the domain?


Task 3C: Taking over the domain

Now that you found the target domain and the hosting provider, make an assumption that the subdomain was running in the app engine of the provider. We will be simulating a small cloud provider which handles their ipv4 allocation by simply provisioning them via roundrobin for any servers joining their app platform.

Visit the imaginary cloud provider management portal at http://hosting-provider.org.localhost:8080/servers/docs
Try out the functionality of the API portal and try to get the IP of the target subdomain under your control
You can see this by monitoring the target subdomain for a change in response
In this case the IP range is very small, and you can perform this task manually. However, in any real scenario the pool of ip addresses would be big enough to warrant automation. Create a script to automatically provision servers until you get the desired domain by utilizing the underlying API of the management portal:


Task D: Hijacking data

Your task is to create an application that collects users that log in to the application and hijacks their session if they navigate to your subdomain page.

If you have trouble receiving the login callback data from the banking application, familiarize yourself with CORS and make required adjustments.

Test your application by creating another user in the banking application and by navigating to your site. You should be able to transfer all their money to your account. You should also be able to receive callbacks from the banking application when users log in.

Place your code in the create_your_server.py file.

Hints
To finish off run docker compose down -v to delete any residual volumes.
