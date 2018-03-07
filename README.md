# ChatBot

ChatBot based on a Insurance Banking Bot to Human User question-answering system.

Domain: Frequently asked questions related to a Insurance Policy pertaining to HDFC Bank.

Requirements for running the code: 
1) Install Pandas:
	pip3.4 install --user pandas
2) Install Numpy:
	pip3.4 install --user numpy


Run:

>> python3.4 corpus_gen.py
>> python3.4 BankFAQbot.py


Details:
* This chat-bot is based on a Insurance Banking Bot to Human User question-answering system.
* Questions were first stored in JSON file, which were originally retrieved from a Banking website.
* The JSON file were then transformed into a CSV file(where the section names were used as class names).
* The CSV file as well as the question asked by the user is processed using tf-idf vectorizing.

* When User asks a question, and the answer is not satisfactory – a list of suggestions of questions is given.

Eg: if a question based on “loan” is asked, few suggestions are given based on “loan” word.

Example Questions:

1) What is meant by disease?
2) Why do I need health insurance?
3) Where can I get the list of hospitals extending the cash facility?
4)  Why should I buy critical illness insurance?
5) What is a Benefit policy?
6) What are pre and post hospitalisations expenses?
7) How do I renew my policy?
8) Who all can be covered under the Family Floater Plan?
9) I am an NRI. Can I invest in this plan?
10) Can the policy be cancelled?
11) Can I buy more than one policy?
12) How do I activate a 'Dormant' Savings Account?
13) What is the frequency of interest payout for a Savings Account?
14) How do I change/Add my Mobile number?
15) How long does the Standing instruction given will be valid?
16) What is CIBIL?
17) What is Pledge?
18) Who can resolve my queries?
19) What is pre-EMI interest?
20) How is online investing more convenient?
