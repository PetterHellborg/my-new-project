# my-new-project
Building AI final project CE-Flow
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

Final project for the Building AI course CE-Flow

## Summary

Describe briefly in 2-3 sentences what your project is about. About 250 characters is a nice length! 
CE Flow is an AI powered application designed to automate the entire CE marking process for industrial products. The platform interprets EU directives, assists with risk assessments, generates documentation, and removes the need for manual handling. The goal is a streamlined, error reduced, and compliant workflow that supports manufacturers in meeting CE standards efficiently.

## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* problem 1: The CE marking process is a legal requirement for accessing the EU market, but it is often slow, complex, and highly dependent on manual work.
Manufacturers frequently struggle with:
•	Identifying applicable directives and harmonized standards
•	Performing and documenting risk assessments

* problem 2: •	Managing large technical files across departments
•	Ensuring up to date compliance documentation

* etc.: These challenges are common across industries such as machinery, industrial equipment, electronics, and automation. Because CE marking is mandatory, delays or errors can prevent market entry, increase costs, or create safety risks.
Personal motivation:
I have observed how much time and resources organizations spend on repetitive, bureaucratic CE compliance tasks. Many of these activities are ideal candidates for automation. This topic matters because CE marking protects end users and ensures product safety — but the administrative load shouldn't hinder innovation or productivity.

## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
CE Flow is intended for:
•	Compliance officers
•	Quality assurance teams
•	Product engineers
•	Manufacturers and industry suppliers
Usage context:
A company enters a product description into the app. CE Flow analyses the information, identifies applicable directives, generates a compliance roadmap, and assembles documentation automatically.
Stakeholders affected:
•	Internal teams benefit from reduced workload and faster time to market.
•	Regulators or auditors receive clearer, more consistent documentation.
•	End users ultimately benefit from increased product safety and compliance consistency.

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)![CE-Flow](https://github.com/PetterHellborg/my-new-project/blob/main/CE-Flow.png)

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)
Data sources required:
•	EU directives and regulations (e.g., Machinery Directive, EMC Directive)
•	Harmonized standards databases
•	Company specific product documentation, test reports, and risk analyses
•	Templates for Declarations of Conformity, technical files, safety instructions
AI techniques that can be used:
•	NLP (Natural Language Processing)
To interpret regulatory texts, classify product categories, and extract required steps from directives.
•	Machine learning classifiers
To match products to relevant standards and directives.
•	Recommendation systems
To propose safety measures, documentation requirements, or risk reduction actions.
•	Document automation and RPA
To auto generate declarations, risk matrices, and technical file structures.
•	Knowledge graph or rule based reasoning
To connect product features with mandatory compliance actions.

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?
Even with automation, CE Flow has limitations:
•	It cannot replace ultimate legal responsibility — companies must still ensure compliance is correct.
•	Regulations change, requiring continuous dataset and model updates.
•	Very specialized or novel products may require human expert judgment.
•	Certain physical tests or measurements cannot be automated through software alone.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 
Possible future development paths:
•	Support for global certifications beyond the EU (e.g., UKCA, UL, CSA).
•	Integration with IoT devices for automated real time risk assessment.
•	Expansion into digital audit trails for inspectors.
•	Collaboration features for complex supply chains.
•	Predictive analytics to foresee compliance risks early in product development.


## Acknowledgments

* list here the sources of inspiration:This project concept builds on publicly available EU regulatory frameworks and inspiration from the Elements of AI – Building AI course structure.
Any future implementation may also rely on:
•	Open source NLP libraries (e.g., spaCy, Hugging Face Transformers)
•	Public EU documentation and harmonized standards lists

 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
