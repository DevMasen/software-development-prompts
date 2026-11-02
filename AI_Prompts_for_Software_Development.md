<a id="top"></a>

# 🤖 AI Prompts for Software Development

> A curated collection of reusable prompts covering the full development lifecycle: planning, architecture, coding, databases, documentation, testing, security and version control.

## 📖 What's Covered

- Project planning and initialization
- Design and architecture decisions
- Code generation and optimization
- Database design and query optimization
- Documentation creation
- Testing and debugging
- Security audits and performance tuning
- Version control and team collaboration

> 💡 **How to use:** Copy a prompt, then replace every `[bracketed placeholder]` with your own details (language, code, schema, etc.) before sending it.

---

## 🧭 Table of Contents

- [🚀 Part 1 · Project Planning & Setup](#p1-planning)
  - [Setting Up a New Project](#p0)
  - [Understanding the AI's Capabilities](#p1)
  - [Creating a Coding Plan](#p2)
  - [Building a Project Knowledge Base](#p3)
  - [Breaking Projects into Components](#p4)
  - [Project Roadmapping](#p5)
  - [Risk Assessment](#p6)
  - [Technology Selection](#p7)
  - [Estimating Project Scope](#p8)
- [🏗️ Part 1 · Design & Architecture](#p1-architecture)
  - [Think Step-by-Step: Architecture](#p9)
  - [Iterating on AI Suggestions](#p10)
  - [Documenting Architecture Decisions (ADR)](#p11)
  - [Choosing Design Patterns](#p12)
  - [Database Schema Design](#p13)
  - [API Design](#p14)
  - [Scalability Considerations](#p15)
- [💻 Part 2 · Code Generation & Review](#p2-code)
  - [Effective Code Generation](#p16)
  - [Explaining Code](#p17)
  - [Code Reviews & Improvements](#p18)
  - [Implementing an Algorithm](#p19)
  - [Creating a Class or Module](#p20)
  - [Optimizing Existing Code](#p21)
  - [Writing Unit Tests](#p22)
- [🗄️ Part 2 · Database Design & Optimization](#p2-database)
  - [Designing a Database Schema](#p23)
  - [Refining a Schema](#p24)
  - [Optimizing SQL Queries](#p25)
  - [Index Optimization](#p26)
  - [Data Migration Planning](#p27)
  - [Query Performance Troubleshooting](#p28)
  - [Database Performance Tuning](#p29)
- [📝 Part 2 · Documentation](#p2-docs)
  - [Generating Documentation](#p30)
  - [Refining Documentation Sections](#p31)
  - [API Documentation](#p32)
  - [README File](#p33)
  - [User Guides](#p34)
  - [Code Comments & Docstrings](#p35)
  - [Living Documentation: Update After Changes](#p36)
  - [Living Documentation: Audit Existing Docs](#p37)
- [🧪 Part 3 · Testing & Debugging](#p3-testing)
  - [Generating Unit Tests](#p38)
  - [Debugging](#p39)
  - [Continuous Code Review](#p40)
  - [Integration Tests](#p41)
  - [Performance Testing](#p42)
  - [Security Testing](#p43)
  - [Test Data Generation](#p44)
- [🔒 Part 3 · Security & Performance](#p3-security)
  - [Full Security Audit](#p45)
  - [Performance Optimization](#p46)
  - [Staying Updated on Best Practices](#p47)
  - [SQL Injection Review](#p48)
  - [Optimizing Resource-Intensive Operations](#p49)
  - [Front-End Security Review](#p50)
- [🔀 Part 3 · Version Control & Collaboration](#p3-git)
  - [Commit Messages](#p51)
  - [Resolving Merge Conflicts](#p52)
  - [Pull Request Reviews](#p53)
  - [.gitignore File](#p54)
  - [Release Notes](#p55)
  - [Branch Naming Conventions](#p56)

---

<a id="p1-planning"></a>

## 🚀 Part 1 · Project Planning & Setup

*Kick off a project, scope it, and plan the work.*

<a id="p0"></a>

### Setting Up a New Project

**Prompt:**

```
I'm starting a new [type of project] using [programming language/framework]. Can you suggest a basic file structure and essential dependencies I should consider?
```

[⬆ Back to top](#top)

<a id="p1"></a>

### Understanding the AI's Capabilities

**Prompt:**

```
What are the key strengths and limitations I should be aware of when using you for software development tasks?
```

[⬆ Back to top](#top)

<a id="p2"></a>

### Creating a Coding Plan

**Prompt:**

```
I want to build [brief project description]. Can you help me break this down into manageable tasks and suggest an order of implementation?
```

> **Tip:** For best results, include these details alongside the prompt above:

1. Project Overview: Start with a brief description of your project. What are you building? What problem is it solving?
2. Tech Stack: List out the languages, frameworks, and tools you’re planning to use.
3. Key Requirements: Outline the main features or functionalities you want to implement.
4. Constraints: Any limitations or specific requirements? Maybe you need to support older browsers or have strict performance criteria.
5. Coding Style: If you have specific coding conventions or architectural preferences, mention them.

> The next prompt (*Building a Project Knowledge Base*) is a ready-made way to provide them.

[⬆ Back to top](#top)

<a id="p3"></a>

### Building a Project Knowledge Base

**Prompt:**

```
I'm starting a new project and I'd like to create a knowledge base for you to reference throughout our development process. The project is [brief description]. We'll be using [tech stack]. The key features we need to implement are [list features]. Some important constraints to keep in mind are [list constraints]. In terms of coding style, we prefer [mention preferences]. Can you summarize this information and suggest any additional details we should include in our knowledge base?
```

[⬆ Back to top](#top)

<a id="p4"></a>

### Breaking Projects into Components

**Prompt:**

```
Based on the project overview we just created, can you help me break down this project into manageable components or modules? For each component, please suggest:
1. A name for the component
2. Its main functionality
3. Potential challenges in implementing it
4. How it might interact with other components
Please also recommend a logical order for developing these components.
```

[⬆ Back to top](#top)

<a id="p5"></a>

### Project Roadmapping

**Prompt:**

```
Using the component breakdown we've created, can you help me develop a project roadmap? Please include:
1. A suggested order for developing the components
2. Estimated time frames for each component (assuming I'm working on this part-time)
3. Potential milestones or checkpoints
4. Any dependencies between components that might affect the development order
5. Suggestions for any proof-of-concept or prototype stages that might be beneficial
```

[⬆ Back to top](#top)

<a id="p6"></a>

### Risk Assessment

**Prompt:**

```
Based on our project plan, can you identify potential risks or challenges we might face during development? For each risk, suggest possible mitigation strategies.
```

[⬆ Back to top](#top)

<a id="p7"></a>

### Technology Selection

**Prompt:**

```
We're considering using [Technology A] or [Technology B] for [specific functionality]. Can you compare these options in the context of our project, considering factors like performance, ease of implementation, and future scalability?
```

[⬆ Back to top](#top)

<a id="p8"></a>

### Estimating Project Scope

**Prompt:**

```
Given our project requirements and component breakdown, can you help me estimate the overall scope of this project? Please provide a rough estimate of the total development time and suggest any areas where we might need to adjust our expectations or seek additional resources.
```

[⬆ Back to top](#top)

---

<a id="p1-architecture"></a>

## 🏗️ Part 1 · Design & Architecture

*Make and record design decisions, schemas, APIs and scaling plans.*

<a id="p9"></a>

### Think Step-by-Step: Architecture

**Prompt:**

```
Let's think step-by-step about the architecture for [specific component or system]. Please consider:
1. The main functionalities this component needs to support
2. Potential data structures or models
3. Key classes or modules and their responsibilities
4. How this component will interact with other parts of the system
5. Potential design patterns that could be applicable
6. Considerations for scalability and maintainability

For each step, provide a brief explanation of your reasoning.
```

[⬆ Back to top](#top)

<a id="p10"></a>

### Iterating on AI Suggestions

**Prompt:**

```
Thank you for that initial design. I have a few follow-up questions:
1. What are the potential drawbacks or limitations of this approach?
2. Can you suggest an alternative design that prioritizes [specific concern, e.g., performance, flexibility]?
3. How would this design need to change if we needed to [potential future requirement]?
```

[⬆ Back to top](#top)

<a id="p11"></a>

### Documenting Architecture Decisions (ADR)

**Prompt:**

```
Based on our discussion of the [component/system] architecture, can you help me create an Architecture Decision Record (ADR)? Please include:
1. The context and problem we're addressing
2. The options we considered
3. The decision we made
4. The consequences (both positive and negative) of this decision
5. Any related decisions or trade-offs
```

[⬆ Back to top](#top)

<a id="p12"></a>

### Choosing Design Patterns

**Prompt:**

```
Given our requirement to [specific functionality], which design patterns might be applicable? For each suggested pattern, please explain how it could be implemented in our system and what benefits it would provide.
```

[⬆ Back to top](#top)

<a id="p13"></a>

### Database Schema Design

**Prompt:**

```
We need to design a database schema for [specific part of the system]. Based on our requirements, can you suggest an initial schema design? Please include tables, key fields, and relationships. Also, consider potential indexing strategies for performance.
```

[⬆ Back to top](#top)

<a id="p14"></a>

### API Design

**Prompt:**

```
We're planning to create a RESTful API for [specific functionality]. Can you help design the endpoints we'll need? For each endpoint, suggest the HTTP method, URL structure, request/response formats, and any authentication requirements.
```

[⬆ Back to top](#top)

<a id="p15"></a>

### Scalability Considerations

**Prompt:**

```
As we design our system, we need to ensure it can scale to handle [expected load]. Can you review our current architecture and suggest modifications or additional components we might need to ensure scalability? Please consider both vertical and horizontal scaling strategies.
```

[⬆ Back to top](#top)

---

<a id="p2-code"></a>

## 💻 Part 2 · Code Generation & Review

*Generate, explain, review and optimize code.*

<a id="p16"></a>

### Effective Code Generation

**Prompt:**

```
I need to implement [specific functionality] in [programming language].
Key requirements:
1. [Requirement 1]
2. [Requirement 2]
3. [Requirement 3]
Please consider:
- Error handling
- Edge cases
- Performance optimization
- Best practices for [language/framework]
Please do not unnecessarily remove any comments or code.
Generate the code with clear comments explaining the logic.
```

[⬆ Back to top](#top)

<a id="p17"></a>

### Explaining Code

**Prompt:**

```
Can you explain the following part of the code in detail:
[paste code section]
Specifically:
1. What is the purpose of this section?
2. How does it work step-by-step?
3. Are there any potential issues or limitations with this approach?
```

[⬆ Back to top](#top)

<a id="p18"></a>

### Code Reviews & Improvements

**Prompt:**

```
Please review the following code:
[paste your code]
Consider:
1. Code quality and adherence to best practices
2. Potential bugs or edge cases
3. Performance optimizations
4. Readability and maintainability
5. Any security concerns
Suggest improvements and explain your reasoning for each suggestion.
```

[⬆ Back to top](#top)

<a id="p19"></a>

### Implementing an Algorithm

**Prompt:**

```
Implement a [name of algorithm] in [programming language]. 
Please include: 
1. The main function with clear parameter and return types 
2. Helper functions if necessary 
3. Time and space complexity analysis 
4. Example usage
```

[⬆ Back to top](#top)

<a id="p20"></a>

### Creating a Class or Module

**Prompt:**

```
Create a [class/module] for [specific functionality] in [programming language].
Include:
1. Constructor/initialization
2. Main methods with clear docstrings
3. Any necessary private helper methods
4. Proper encapsulation and adherence to OOP principles
```

[⬆ Back to top](#top)

<a id="p21"></a>

### Optimizing Existing Code

**Prompt:**

```
Here's a piece of code that needs optimization:
[paste code]
Please suggest optimizations to improve its performance. For each suggestion, explain the expected improvement and any trade-offs.
```

[⬆ Back to top](#top)

<a id="p22"></a>

### Writing Unit Tests

**Prompt:**

```
Generate unit tests for the following function:
[paste function]
Include tests for:
1. Normal expected inputs
2. Edge cases
3. Invalid inputs
Use [preferred testing framework] syntax.
```

[⬆ Back to top](#top)

---

<a id="p2-database"></a>

## 🗄️ Part 2 · Database Design & Optimization

*Schemas, queries, indexes, migrations and tuning.*

<a id="p23"></a>

### Designing a Database Schema

**Prompt:**

```
I'm designing a database for [describe your application]. The main entities are:
[List main entities]

Key requirements:
1. [Requirement 1, e.g., "Must support fast retrieval of user posts"]
2. [Requirement 2, e.g., "Need to track user relationships (followers/following)"]
3. [Requirement 3, e.g., "Must handle large volumes of time-series data for analytics"]

Please suggest a database schema that includes:
1. Tables and their columns (with appropriate data types)
2. Primary and foreign key relationships
3. Any necessary junction tables for many-to-many relationships
4. Suggested indexes for performance
5. Considerations for scalability

Also, please explain the rationale behind your design choices.
```

[⬆ Back to top](#top)

<a id="p24"></a>

### Refining a Schema

**Prompt:**

```
Given this initial schema:
[Paste your schema here]

Please analyze it considering the following:
1. Normalization: Is the schema properly normalized? If not, suggest improvements.
2. Denormalization: Are there any cases where denormalization might improve performance?
3. Indexing strategy: Suggest additional indexes that might improve query performance.
4. Scalability: How will this schema handle growth? Any potential bottlenecks?
5. Data integrity: Are there any constraints or triggers we should consider to ensure data consistency?
For each suggestion, please explain the pros and cons.
```

[⬆ Back to top](#top)

<a id="p25"></a>

### Optimizing SQL Queries

**Prompt:**

```
I need to optimize the following SQL query:
[Paste your query here]

The query is currently taking too long to execute on large datasets. Please:
1. Analyze the query and identify potential performance issues.
2. Suggest optimizations, which may include:
   - Rewriting the query
   - Adding or modifying indexes
   - Suggestions for schema changes if necessary
3. Explain the reasoning behind each optimization.
4. If possible, provide an estimate of the performance improvement we might expect.
Additional context:
- Database system: [e.g., PostgreSQL, MySQL]
- Approximate table sizes: [e.g., Users table has 1 million rows]
- Any relevant hardware constraints
```

[⬆ Back to top](#top)

<a id="p26"></a>

### Index Optimization

**Prompt:**

```
Given the following table structure and common queries:
[Paste table structure and sample queries]

Please suggest an optimal indexing strategy. Consider:
1. Which columns should be indexed?
2. Should we use single-column or multi-column indexes?
3. Are there any cases where a covering index would be beneficial?
4. How might these indexes affect write performance?
```

[⬆ Back to top](#top)

<a id="p27"></a>

### Data Migration Planning

**Prompt:**

```
I need to migrate data from an old schema to a new one:
Old schema:
[Paste old schema]

New schema:
[Paste new schema]

Please help me create a migration plan:
1. Identify the steps needed to transform the data
2. Suggest any intermediate tables or views that might be helpful
3. Consider data integrity and how to handle potential conflicts
4. Propose a strategy to verify the migration's success
```

[⬆ Back to top](#top)

<a id="p28"></a>

### Query Performance Troubleshooting

**Prompt:**

```
The following query is performing poorly:
[Paste problematic query]

Execution plan:
[Paste execution plan if available]

Please analyze this query and suggest improvements:
1. Identify any sub-optimal parts of the query or execution plan
2. Suggest alternative ways to write the query
3. Are there any missing indexes that could help?
4. Would denormalizing any part of the schema improve performance for this query?
```

[⬆ Back to top](#top)

<a id="p29"></a>

### Database Performance Tuning

**Prompt:**

```
I'm looking to improve the overall performance of my database. Here's an overview:
- Database system: [e.g., PostgreSQL 13]
- Current size: [e.g., 500GB]
- Main tables and their sizes: [List main tables]
- Common query patterns: [Describe typical queries]
- Current pain points: [e.g., slow joins on large tables, poor write performance during peak hours]

Please provide a comprehensive performance tuning plan, including:
1. Configuration parameters that might need adjustment
2. Indexing strategy review
3. Query optimization techniques
4. Potential schema optimizations
5. Caching strategies
6. Any other relevant suggestions for improving performance
For each suggestion, please explain the expected impact and any potential trade-offs.
```

[⬆ Back to top](#top)

---

<a id="p2-docs"></a>

## 📝 Part 2 · Documentation

*Docs, READMEs, API references, comments and living docs.*

<a id="p30"></a>

### Generating Documentation

**Prompt:**

```
I need to create documentation for [project/component name]. Please generate:

1. An overview of the [project/component]
2. Installation instructions
3. Configuration options
4. API reference (if applicable)
5. Usage examples
6. Troubleshooting guide
7. FAQ section

For each section, consider:
- The target audience (e.g., developers, end-users)
- Any prerequisites or dependencies
- Common pitfalls or misconceptions
- Best practices

Please use clear, concise language and include relevant code snippets where appropriate.
```

[⬆ Back to top](#top)

<a id="p31"></a>

### Refining Documentation Sections

**Prompt:**

```
Please review and improve the following documentation section:
[Paste section here]

Consider:
1. Clarity of explanation
2. Completeness of information
3. Appropriate level of detail for the target audience
4. Consistency with best practices in technical writing
Suggest improvements and explain your reasoning.
```

[⬆ Back to top](#top)

<a id="p32"></a>

### API Documentation

**Prompt:**

```
Generate API documentation for the following endpoint:
[Paste endpoint details]
Include:
1. Endpoint URL and method
2. Request parameters and their types
3. Request body format (if applicable)
4. Response format and possible status codes
5. Example request and response
6. Any authentication requirements
7. Rate limiting information (if applicable)
```

[⬆ Back to top](#top)

<a id="p33"></a>

### README File

**Prompt:**

```
Create a README.md file for my GitHub repository. The project is [brief description]. Include:
1. Project title and description
2. Installation instructions
3. Usage examples
4. Contributing guidelines
5. License information
6. Badges (e.g., build status, version, etc.)
Use proper Markdown formatting and consider adding a table of contents for easier navigation.
```

[⬆ Back to top](#top)

<a id="p34"></a>

### User Guides

**Prompt:**

```
Generate a user guide for [product/feature name]. The target audience is [describe audience]. Include:
1. Introduction and purpose of the product/feature
2. Getting started guide
3. Main features and how to use them
4. Advanced usage tips
5. Troubleshooting common issues
Use simple language and consider including step-by-step instructions with hypothetical screenshots placeholders.
```

[⬆ Back to top](#top)

<a id="p35"></a>

### Code Comments & Docstrings

**Prompt:**

```
Generate appropriate comments and docstrings for the following code:
[Paste code here]
Follow [language-specific] conventions for docstrings. Include:
1. Brief description of the function/class
2. Parameters and their types
3. Return value and type
4. Any exceptions that might be raised
5. Usage examples if the function/class usage is not immediately obvious
```

[⬆ Back to top](#top)

<a id="p36"></a>

### Living Documentation: Update After Changes

**Prompt:**

```
I've made the following changes to my code:
[Summarize changes]
Please update the relevant sections of the documentation to reflect these changes. 
Highlight any breaking changes or new features that users should be aware of.
```

[⬆ Back to top](#top)

<a id="p37"></a>

### Living Documentation: Audit Existing Docs

**Prompt:**

```
Please review the following documentation:
[Paste current docs]
Considering the latest best practices and common user pain points in similar projects:
1. Suggest any sections that should be added or expanded
2. Identify any parts that might be outdated or no longer relevant
3. Recommend improvements for clarity and user-friendliness
```

[⬆ Back to top](#top)

---

<a id="p3-testing"></a>

## 🧪 Part 3 · Testing & Debugging

*Unit, integration, performance and security tests plus debugging.*

<a id="p38"></a>

### Generating Unit Tests

**Prompt:**

```
I need unit tests for the following function:
[Paste your function here]

Please generate a comprehensive set of unit tests that cover:
1. Happy path scenarios
2. Edge cases
3. Error conditions
4. Boundary value analysis

For each test case, please:
1. Provide a brief description of what the test is checking
2. Write the actual test code using [preferred testing framework, e.g., pytest]
3. Explain any mock objects or fixtures that might be needed

Also, suggest any additional tests that might be relevant based on common pitfalls or best practices for this type of function.
```

[⬆ Back to top](#top)

<a id="p39"></a>

### Debugging

**Prompt:**

```
I'm encountering the following bug:
[Describe the bug, including any error messages and the steps to reproduce]

Here's the relevant code:
[Paste the code related to the bug]

Please help me debug this issue:
1. Analyze the code and suggest potential causes of the bug
2. Provide step-by-step debugging strategies I can follow
3. Suggest any tools or techniques that might be helpful in diagnosing the issue
4. If possible, propose potential fixes and explain their reasoning

Additionally, are there any best practices or common pitfalls related to this type of issue that I should be aware of for future reference?
```

[⬆ Back to top](#top)

<a id="p40"></a>

### Continuous Code Review

**Prompt:**

```
Please review the following code for quality and potential issues:
[Paste your code here]

In your review, please consider:
1. Code style and adherence to best practices
2. Potential bugs or edge cases not handled
3. Performance optimizations
4. Security vulnerabilities
5. Readability and maintainability

For each issue found, please:
1. Explain the problem
2. Suggest a fix
3. Provide a brief rationale for the suggested change

Additionally, are there any overall improvements or refactoring suggestions you would make for this code?
```

[⬆ Back to top](#top)

<a id="p41"></a>

### Integration Tests

**Prompt:**

```
I need to create integration tests for the following components:
[List components and their interactions]

Please suggest a set of integration tests that:
1. Cover the main interaction scenarios between these components
2. Test for proper error handling and edge cases
3. Include any necessary setup and teardown procedures

Provide the test scenarios in a clear, step-by-step format, and include any necessary mock objects or test data.
```

[⬆ Back to top](#top)

<a id="p42"></a>

### Performance Testing

**Prompt:**

```
I need to create a performance test plan for my application. The key areas of concern are:
[List main functionalities or components to be tested]

Please help me create a performance test plan that includes:
1. Key performance indicators to measure
2. Test scenarios to simulate various load conditions
3. Suggestions for tools or frameworks to use
4. Strategies for identifying performance bottlenecks
5. Best practices for interpreting and acting on the results
```

[⬆ Back to top](#top)

<a id="p43"></a>

### Security Testing

**Prompt:**

```
Please review the following code for potential security vulnerabilities:
[Paste your code]

Consider common security issues such as:
1. Injection flaws
2. Broken authentication
3. Sensitive data exposure
4. XML external entities (XXE)
5. Broken access control
6. Security misconfigurations
7. Cross-site scripting (XSS)

For each vulnerability found, explain the risk and suggest secure coding practices to mitigate it.
```

[⬆ Back to top](#top)

<a id="p44"></a>

### Test Data Generation

**Prompt:**

```
I need to generate test data for the following database schema:
[Paste your schema here]

Please help me create a test data generation plan:
1. Suggest appropriate ranges or types of values for each field
2. Provide SQL or script to generate a diverse set of test data, including:
   - Normal cases
   - Edge cases
   - Invalid data to test error handling
3. Ensure referential integrity is maintained for related tables
4. Include any specific scenarios or data patterns crucial for thorough testing

The test data should be comprehensive enough to cover various testing scenarios while remaining manageable in size.
```

[⬆ Back to top](#top)

---

<a id="p3-security"></a>

## 🔒 Part 3 · Security & Performance

*Audits, hardening and performance tuning.*

<a id="p45"></a>

### Full Security Audit

**Prompt:**

```
Please perform a security audit on the following code:
[Paste your code here]

In your audit, please:
1. Identify any potential security vulnerabilities, including but not limited to:
   - Injection flaws (SQL, NoSQL, OS command injection, etc.)
   - Broken authentication
   - Sensitive data exposure
   - XML External Entities (XXE)
   - Broken access control
   - Security misconfigurations
   - Cross-Site Scripting (XSS)
   - Insecure deserialization
   - Using components with known vulnerabilities
   - Insufficient logging & monitoring
2. For each vulnerability found:
   - Explain the potential impact
   - Suggest a fix or mitigation strategy
   - Provide a code snippet demonstrating the fix, if applicable
3. Suggest any general security improvements or best practices that could be applied to this code.
4. Recommend any security-related libraries or tools that could help improve the overall security posture of the application.

This comprehensive prompt usually gives me a solid starting point for hardening my application’s security.
```

[⬆ Back to top](#top)

<a id="p46"></a>

### Performance Optimization

**Prompt:**

```
Please analyze the following code for performance optimization opportunities:
[Paste your code here]

In your analysis, please:
1. Identify any performance bottlenecks or inefficient operations
2. Suggest optimizations, considering:
   - Time complexity improvements
   - Memory usage optimization
   - Reduction of unnecessary operations or function calls
   - Potential for parallelization or asynchronous operations
   - Caching strategies
3. For each suggestion:
   - Explain the expected performance impact
   - Provide a code snippet demonstrating the optimization
   - Discuss any potential trade-offs (e.g., readability, maintainability)
4. Recommend any language-specific performance best practices or libraries that could be beneficial
5. Suggest any profiling tools or techniques that could help further analyze the performance in a real-world scenario
```

[⬆ Back to top](#top)

<a id="p47"></a>

### Staying Updated on Best Practices

**Prompt:**

```
Please provide an update on the latest best practices for [your language/framework] as of [current date], focusing on:
1. Security enhancements and newly discovered vulnerabilities
2. Performance optimization techniques
3. New language features or libraries that could improve security or performance
4. Any deprecated practices that should be avoided

For each point, please explain:
- What the practice or vulnerability is
- Why it's important
- How to implement or mitigate it in practical terms
```

[⬆ Back to top](#top)

<a id="p48"></a>

### SQL Injection Review

**Prompt:**

```
Please review the following database interaction code for potential SQL injection vulnerabilities:
[Paste your database interaction code]

For each vulnerability found:
1. Explain how it could be exploited
2. Provide a secure alternative implementation
3. Suggest any relevant security libraries or techniques specific to our database system
```

[⬆ Back to top](#top)

<a id="p49"></a>

### Optimizing Resource-Intensive Operations

**Prompt:**

```
The following function is causing performance issues in our application:
[Paste your function]

Please suggest ways to optimize this function, considering:
1. Time complexity improvements
2. Memory usage optimization
3. Potential for caching or memoization
4. Opportunities for parallel processing, if applicable

For each suggestion, provide a brief explanation of the expected performance gain and any potential trade-offs.
```

[⬆ Back to top](#top)

<a id="p50"></a>

### Front-End Security Review

**Prompt:**

```
Please review the following front-end code for security best practices:
[Paste your front-end code]

Consider aspects such as:
1. Cross-Site Scripting (XSS) prevention
2. Secure handling of sensitive data
3. Protection against Cross-Site Request Forgery (CSRF)
4. Secure communication with back-end APIs

Provide specific recommendations for improving the security of this code, including any relevant libraries or techniques for our front-end framework.
```

[⬆ Back to top](#top)

---

<a id="p3-git"></a>

## 🔀 Part 3 · Version Control & Collaboration

*Commits, merges, PRs, releases and conventions.*

<a id="p51"></a>

### Commit Messages

**Prompt:**

```
I've made the following changes to my code:
[Paste your git diff or describe the changes]

Please help me create a commit message that:
1. Summarizes the changes concisely (50 characters or less for the subject line)
2. Provides more details in the body (wrap at 72 characters)
3. Follows best practices for git commit messages
4. Includes any relevant issue numbers or references

The commit message should be informative enough that team members can understand the changes without having to look at the code.
```

[⬆ Back to top](#top)

<a id="p52"></a>

### Resolving Merge Conflicts

**Prompt:**

```
I'm facing the following merge conflict:
[Paste the conflicting code sections]

The feature I'm trying to merge aims to: [Briefly describe the feature's purpose]

Please help me resolve this conflict by:
1. Analyzing both versions of the code
2. Suggesting the best way to combine the changes
3. Providing a resolved version of the code
4. Explaining the reasoning behind the suggested resolution

Also, please advise if there are any potential issues or side effects I should be aware of after this merge.
```

[⬆ Back to top](#top)

<a id="p53"></a>

### Pull Request Reviews

**Prompt:**

```
Please review the following pull request:
[Paste the PR diff or provide a summary of changes]

In your review, please:
1. Identify any potential issues or improvements in the code
2. Check for adherence to our project's coding standards and best practices
3. Suggest any tests that might be needed
4. Point out any parts of the code that might need more documentation
5. Highlight any security or performance concerns

For each point, provide a brief explanation and, if applicable, suggest how it could be addressed.
```

[⬆ Back to top](#top)

<a id="p54"></a>

### .gitignore File

**Prompt:**

```
I'm starting a new [language/framework] project. Please help me create a comprehensive .gitignore file that:
1. Excludes common system and IDE files
2. Ignores language-specific build artifacts and dependencies
3. Ensures no sensitive information (like API keys) is accidentally committed

Please provide explanations for any non-obvious entries.
```

[⬆ Back to top](#top)

<a id="p55"></a>

### Release Notes

**Prompt:**

```
We're preparing to release version [X.Y.Z] of our software. Based on the following commit history since our last release:
[Paste relevant commit history]

Please help me draft release notes that:
1. Summarize key new features
2. List any breaking changes and migration steps
3. Mention bug fixes and performance improvements
4. Thank contributors (if applicable)

The tone should be professional but friendly, suitable for both technical and non-technical readers.
```

[⬆ Back to top](#top)

<a id="p56"></a>

### Branch Naming Conventions

**Prompt:**

```
Our team needs a consistent branch naming convention. Please suggest a branch naming strategy that:
1. Clearly indicates the type of work (e.g., feature, bugfix, hotfix)
2. Includes relevant ticket or issue numbers
3. Is concise but descriptive

Provide examples for different scenarios and explain the rationale behind the suggested convention.
```

[⬆ Back to top](#top)

---
