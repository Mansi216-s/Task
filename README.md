This project contains three services: ProductMatrixService, PredictiveModelService, and ApplicationService.

The ProductMatrixService is responsible for maintaining a list of products for a lender along with specific requirements that must be met for loan approval to be 

granted in which Requirements include:
applicant_age > 18
credit_score > 500
min_loan_amount >= $10,000
Optional rules may also be defined and the service can be accessed via REST API endpoints.

In the PredictiveModelService, it incorporates the results obtained from a machine learning model for each lender's product.A higher confidence_score is indicative of 

a greater likelihood of loan approval by the lender.Confidence_scores exceeding 80 are deemed to be among the top selected lenders and service can be accessed via REST 

API endpoints.

In the ApplicationService, it serves to indicate the status of the loan application.The service indicates whether a loan application has been approved or declined and 

includes lender Id.The service is currently in the architectural design phase and requires further development.The service can be accessed via REST API endpoints.

Technology Stack:
Java 11
Spring Boot
Liquibase

To run this Project,first Clone the repository,add the necessary dependencies,Run the services,Access the services via REST API endpoints which already mentioned in 

separate API.
