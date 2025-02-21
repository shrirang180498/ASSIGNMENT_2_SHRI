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

## Functional Requirements

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

