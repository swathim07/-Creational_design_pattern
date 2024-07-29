# -Creational_design_pattern
Use Case 1: Singleton Pattern
Scenario: A configuration manager that ensures only one instance of the configuration settings exists throughout the application.
•	ConfigurationManager Class: This class ensures that only one instance of the configuration settings exists. It uses a private constructor to prevent instantiation from other classes
and a static method to provide access to the single instance.
•	getInstance Method: Ensures that the instance is created only once, using double-checked locking for thread safety.
•	Properties: A simple way to manage configuration settings, which can be loaded from a file or set programmatically.

Use Case 2: Factory Method Pattern
Scenario: A simple document editor application that supports creating different types of documents (e.g., Word, PDF).
•	Document Interface: Defines the common operations for all types of documents (open and save).
•	WordDocument and PDFDocument Classes: Implement the Document interface, providing specific implementations for Word and PDF documents.
•	DocumentCreator Abstract Class: Declares the factory method (createDocument) and provides methods to open and save documents using the product created by the factory method.
•	WordDocumentCreator and PDFDocumentCreator Classes: Implement the factory method to create specific types of documents.

