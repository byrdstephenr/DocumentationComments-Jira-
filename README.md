**Jira Ticket Management Tool**

This is a Python-based tool to automate Jira ticket management. It uses the Jira API to retrieve ticket information, add comments, and transition tickets.

**Prerequisites**

	Python 3.x
	Python requests library
	Python jira library
	Jira URL, API token, and username with appropriate permissions
	Getting Started
	Clone the repository:
	git clone https://github.com/your-username/jira-ticket-management.git
	cd jira-ticket-management
	Install the required libraries:
	python main.py


**Functionality**

	Pull Ticket Information Function: pull_ticket_info(jql_query, jira_url, api_token, jira_username) Description: Retrieves ticket information from Jira using a JQL query and prints ticket details (ticket number, summary, request type, research type).
	
 	Get Comments Function: get_comments(ticket_number, jira_url, api_token, jira_username) Description: Retrieves comments for a specific ticket and returns the comment text.
	
 	Add Comment Function: add_comment_with_jira_library(ticket_number, research_type, jira_url, api_token, jira_username) Description: Adds a comment to a Jira ticket using the jira library. The comment includes documentation links based on the research type.
	
 	Transition Ticket Function: transition_ticket(ticket_number, transition_id, jira_url, api_token, jira_username) Description: Transitions a Jira ticket to a specific status using the Jira API. Usage Modify the documentation_dict variable in main.py with your documentation links for different research types.
	
 	Update the JQL query in main.py to retrieve the relevant tickets.

	Customize and extend the functions in main.py based on your specific requirements.

Contributing Contributions are welcome! If you have any suggestions, bug fixes, or new features to add, feel free to open an issue or submit a pull request.

Remember to update the placeholders (e.g., `your-username`, `https://your-jira-instance.atlassian.net`, etc.) with the actual values specific to your project.
You will also need to create your own dictionary of documentation.


	License This project is licensed under the MIT License.

