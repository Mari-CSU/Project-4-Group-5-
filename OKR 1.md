

---

## (1.C.1.1) OKR 1 (User Safety)

Companon is designed to ensure the safety of users above all else. It is important that the system is able to recognize when a user is in a high-risk mental state and to provide the appropriate resources. Key stakeholders consist of primarily young adults and, as they are the most at-risk group for adverse mental health. Secondary stakeholders also include crisis hotlines, therapists, and mental-health advocates. Many young adults lack the financial resources for adequate mental health services, so Companon is designed to help link these two groups together.  

---

## (1.C.1.2) Metric(s) with Experimentation 

The main goal of OKR 1 is to provide a user with adequate care based on the responses they share with the chat bot. A question then arises about how the AI will be able to determine a high-risk user. To do this, it is important to understand how an AI (really an LLM in this scenario) determines “good” and “bad” input.  

In the article *How Large Language Models Work* (IBM, 2023), within *Machine Learning*, it highlights how a model is able to distinguish between two genres of music. The initial sample size starts with 20 songs, each labeled with a genre, tempo, and energy. By determining what tempo and energy generally correlate with a certain genre, the LLMs are able to predict what genre a song belongs to.  

This same methodology can be applied to Companon. By taking transcripts of real-world mental health interactions, the AI can build an understanding of how to correctly respond to our constituents.  

To help the AI determine good/bad results, I propose this training and testing process:

1. The AI must be presented with real-world transcripts to base its training on. In this first phase, we would manually determine if the chatbot’s response is appropriate and continue with iterations we deem successful.  
2. Once the AI consistently produces “good” results, focus testing can begin. A group of young adults will be brought in to “break” the program. The goal is to have users give extreme and outlandish inputs to really stress test the system. Once the system has been thoroughly tested, it is then ready for public release.  

In addition, it is important to consult with actual mental health professionals when determining the quality of results.  

---

## (1.C.1.3) Ethical Impact(s)/Issues 

There is an inherent risk when trying to design an AI companion, especially one that is reliant on trying to improve mental health. There are numerous real world examples where people have become overly attached to AI, often using them as supplements for real world interaction. One such example being the ELIZA effect.  

The ELIZA effect is based on a phenomenon where computer scientist Joseph Weizenbaum observed that people became overly attached to a chatbot program named ELIZA. One of the program scripts was designed to emulate a psychotherapist, where the chatbot would respond either generically or rephrase whatever the user typed. While simple, people did end up forming an attachment with the program, often getting deeply personal with the chatbot.  

---

## Stakeholder Financial Risk Privacy Risk Conflicting Interest

| Stakeholder | Financial Risk | Privacy Risk | Conflicting Interest |
|--------------|----------------|---------------|----------------------|
| Customer | Low | High | Mid |
| Mental Health Professionals | Low | Low | Low |
| The Company | High | Low | Mid |

---

### Customer

Companon’s business model is designed to emulate existing AI business models; i.e., it will be a free product which runs off billions of dollars of investor funding while also containing a premium enhanced version. This makes the financial investment in customers low, with the only potential transactions being between mental health professionals.  

Since Companon relies on collecting anonymous user data, this inherently puts the customer at a high privacy risk.  

Regarding conflicting interests, customers may not be keen on sharing their mental troubles with a chatbot.  

---

### Mental Health Professionals

While there is an idea of having professionals pay the company to advertise their services, this is optional. The burden of connection between patients and clients lies with the company.  

Since professionals tend to advertise themselves (either via websites, posters, bookings, etc.), any personal information they're willing to present is already out there.  

Since Companon essentially acts as advertisement for professionals, there is little conflicting interest.  

---

### Company

It’s up to the company to make its investments back and fulfill shareholder needs.  
The company is risking little in terms of privacy, although there are cybersecurity measures to worry about.  
There is a conflicting interest between the company and the customers. The company must make a profit, which comes at the expense of the customer. This can lead to customer backlash, creating friction between the company and customer.  

---

## (1.C.1.4) Ethical Safeguards 

Who would design the safeguard?  

Since the priority of Companon is the safety of the company’s users, the company would mainly hire AI Ethicists, Cyber Security Experts, and mental health consultants.  

As stated in the OKR, the limits of the AI will be rigorously tested against the company’s internal testers. Test methods will include testing such as model evaluation, stress testing, and security testing.  

---

