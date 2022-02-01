
# Data Dictionary vs. Business Glossary: Benefits, Challenges, and Solutions

In your organization, are you ever confused by different definitions of business terms? Do you ever wonder why the number of customers differs between two reports?
I’m going to assume the answer is “yes.” And you are not alone.

As an organization evolves, it’s natural for the language to evolve, too. That’s why it’s critical that important terms be defined, documented, and made visible to everyone. This aligns understanding, so that, for example, a term like “customer” means the same thing across all departments.
This is where a data dictionary and business glossary become useful for getting both your business and IT teams on the same page.
Calvin and Hobes comic snippet where Calvin is asking Hobes the definition to a long word.

### What is a data dictionary?
A data dictionary defines and describes technical data terms. Data terms could be database schemas, tables, or columns. It may include information about the data type, size, default values, constraints, relationships to other data, and the meaning or purpose of a given asset.

### Who benefits from a data dictionary?
Data dictionaries are designed for more technical audiences, like IT or data scientists.

These folks will reference the data dictionary to understand data elements, which allows them to manage, move, merge, and analyze data with clarity.

For complex projects, like data wrangling, modeling, or database design, a data dictionary is a helpful resource. This is especially true for new hires. For these tasks, they may look to the data dictionary to ensure use of the right assets.

## What is a business glossary?
A business glossary defines and describes business terms and organizational nomenclature.

If you’re thinking “business term definitions” are straightforward, think again. For businesses operating across many departments, regions, and contexts, a single term can have multiple meanings. This can become confusing and result in costly mistakes.
For example, to the sales department, the term “revenue” may include gift cards, but not to the finance department. “Customers” and “users” might sound the same, but they are accounted for differently depending on who you ask. The term “beta feature” may be clear internally, but not to the Customer Success team, who communicate with customers.
Simply put, having a clear definition and understanding of business terms is extremely useful for any enterprise.

## Who benefits from a business glossary?
A business glossary is useful for the business audience, or people working in functional departments, such as finance, marketing, or sales. When new people join an organization, they can look to the business glossary to learn the business language.
A business glossary helps an organization agree and align on internal definitions. How often have you faced a problem where you think a business term means one thing, but another team believes it means something else? If an executive is presented with two different reports describing the same term, without context on why they differ, how will they react? In all likelihood, they will distrust both reports.
Another benefit of the business glossary is self-service. Users can help themselves without asking around to find an answer. This in itself promotes efficiency and productivity for everyone.

What are the Differences Between a Data Dictionary and a Business Glossary?
Here’s an outline of how a data dictionary and a business glossary differ:



## What are the Challenges of a Data Dictionary and Business Glossary?
We’ve established the value of both a data dictionary and business glossary. Now the question becomes, how to create them?
On the surface, both sound easy and straightforward to develop. But there are indeed inherent challenges.

### Data Dictionary Challenges
For a data dictionary, the volume of new data is constantly increasing. This makes it difficult to keep up with all the new data elements that need to be defined. To keep pace, IT or database administrators may automate data dictionary maintenance. Automation helps IT build and preserve the integrity of the data dictionary.

### Business Glossary Challenges
For a business glossary, it’s important to assign ownership. Definitions may differ depending on context or team. You must ask:
Who is responsible for defining the terms?
Are definitions set by one person or by group consensus?
Is there an approval process?
These challenges require both a robust process and tool to manage a business glossary.

### How to use a data dictionary and business glossary with Alation

Alation is a machine learning data catalog. Once connected to data sources in the environment, Alation automatically indexes data and populates catalog pages by source. Let’s take a look at how the Alation Data Dictionary and Business Glossary produce and simplify vocabulary complexities:

### The Alation Data Dictionary
In the example below, a data dictionary of columns in the “metrics” table has been generated. In Alation, this is what a data dictionary looks like:
Alation's data dictionary displaying the columns section.
This table shows the technical column name, a business title name, the data type, and popularity. Users can click on the blue column links to get more information and context about the columns.

Machine Learning and the Behavioral Analysis Engine (BAE)
Note that the business “Title” names are auto-titled. Machine learning translates the technical column names into natural human language. For example, “ts_created” has been identified as “Timestamp Created” by the machine and confirmed by a person. This is indicated by the green robot head, AKA Allie.
“Popularity” is an Alation-specific measure of how much the column has been searched and queried by the users. This is calculated automatically through Alation’s Behavioral Analysis Engine (BAE). It does so by accounting for how frequently and recently the columns have been used.
Having insight into the popularity of data is useful. This is because it lets people know what data is most worthy of their attention. It also offers insight into the data that is most trusted, a good indicator of quality.

### The Alation Business Glossary

The business glossary in Alation is more than a place to look up terms and definitions, or assign owners. There are some unique features that make Alation’s business glossary easier to manage and scale. Each glossary is made up of a collection of terms. For example, the “Financial KPI Metrics” glossary may include terms for “EBIT”, “CACC”, and ‘“Debt-to-equity” ratio. The Glossary columns can be customized for different fields, such as”‘Author”, “Description”, or “Status.”
To keep the glossary layout consistent, templates can be applied so that all terms contain the same useful information.
