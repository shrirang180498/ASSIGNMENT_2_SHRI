# Name: Shrirang Raval
# Student ID: 8958825
# Assignemnt-2 : Requirement 
# Professor: PROF. ANDY CHOW



---

# Problem Summary:
The client, an AI developer, uses web scraping to gather training data but faces challenges in organizing and ensuring the quality of this data. Specifically, they need a system that:

- **Categorizes training questions separately from answers to support developer self-affirmation. **
- **Ensures balanced training data (free from biases) to improve AI model performance. **

---


# 1. Requirement Breakdown

## Functional Requirements:

#### Categorized Training Questions:
- Developers should be able to classify training questions using the system according to subjects, degrees of difficulty, or other pertinent factors.
- The system ought to include a user interface (UI) that makes it simple for developers to categorize and tag questions.
- To encourage self-affirmation, the system should make sure that questions and replies are kept apart.

#### Balanced Training Data:
- The system ought to have a function that checks the training data for biases, such as racial, gender, or cultural prejudices.
- To maintain balance, the system ought to offer a summary or dashboard that illustrates how data is distributed across various categories.
- The technology must enable developers to eliminate or lessen biases by filtering or modifying the dataset.

## System Requirements:

#### Scalability:
- Performance deterioration should not occur when handling massive datasets, such as millions of questions and responses.
- Parallel processing should be supported by the system to expedite data classification and analysis.

#### Data Protection:
- All information (questions, responses, and metadata) should be safely stored by the system, encrypted both in transit and at rest.
- To guarantee that only developers with permission can view or alter the data, the system should incorporate access control.

#### Combining Web Scraping Tools:
- The system should easily interface with the client's current web scraping technologies so that data may be imported straight into the system.
- For simple data import and export, the system should support a variety of data formats, such as CSV and JSON.



---


# 2. Assumptions & Validations

## Assumptions:

#### Availability of Data:
- For web scraping, we presume that the client has access to enough publicly available data.
- We presume that the web scraping techniques used by the client are dependable and capable of delivering consistent data.

#### User Proficiency:
- We presume that the system's developers are familiar with the fundamentals of data management and AI training.
- We presume that the developers are knowledgeable with data formats and online scraping tools.

#### Environment of the System:
- We anticipate that the system will be set up in a cloud environment with enough resources for performance and scalability.




## Validations:

#### Validation Plan:
1. **Customer Evaluation:**
   - Show the client the specifications and presumptions for approval and comments.
   - To make sure the requirements match the client's expectations, have a workshop or meeting.

2. **Testing Prototypes:**
   - Create a system prototype with fundamental features (such as bias analysis and classification) and test it on a small dataset.
   - To improve the requirements, get input from the developers and the client.

3. **Analyzing Data:**
   - To verify the bias analysis function and make sure it offers precise and useful insights, use a sample dataset.
   - To make sure the categorization functionality functions as intended, test it with various kinds of data.


---






# 3. TASK BREAKDOWN- Actions to follow:


## Task 1: Collecting and Analyzing Requirements
- **Subtasks:**
  - Have meetings with the client to collect specific needs.
  - Examine the present difficulties and record the system and functional needs.
  - Consult the customer to confirm the needs.

## Task 2: System Architecture
- **Subtasks:**
  - Create the system architecture, taking into account the processing, storage, and data flow elements.
  - Make user interface prototypes or wireframes.
  - Identify the sites of integration with web scraping technologies.

## Task 3: Execution
- **Subtasks:**
  - Create the training question classification feature.
  - Put the reporting and bias analysis tool into use.
  - Include web scraping tools in the system.

## Task 4: Validation and Testing
- **Subtasks:**
  - To make sure the system satisfies the requirements, test it using example datasets.
  - Get input from the client and validate the system.
  - Resolve any problems found during testing.

## Task 5: Documentation and Deployment
- **Subtasks:**
  - Install the system in a cloud setting.
  - Give developers instructions on how to operate the system.
  - Provide the client's developers with training.


---

## Other Assumptions:
### 1. Future-Proofing Assumptions
- **Extensibility**: The system should accommodate future features.
- **Data Growth**: The system should handle increasing data volumes.
- **Technology Updates**: The system should be compatible with future updates.

### 2. User Feedback Assumptions
- **Feedback Loop**: The system should include a feedback mechanism.
- **Iterative Development**: The client is open to iterative improvements.
