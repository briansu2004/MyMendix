# MyMendix Course

- [Lectures](#lectures)
  - [(Optional) Big issues for long time](#optional-big-issues-for-long-time)
  - [(Optional) Personal feelings about Mendix and Low Code](#optional-personal-feelings-about-mendix-and-low-code)
  - [Mendix Version Selector](#mendix-version-selector)
  - [Mendix Quickstart](#mendix-quickstart)
    - [Step 1: Download and Install Mendix Studio Pro](#step-1-download-and-install-mendix-studio-pro)
    - [Step 2: Sign Up for a Mendix Account](#step-2-sign-up-for-a-mendix-account)
    - [Step 3: Create a New Mendix App](#step-3-create-a-new-mendix-app)
    - [Step 4: Define Your App](#step-4-define-your-app)
    - [Step 5: Model Your Data](#step-5-model-your-data)
    - [Step 6: Design Your App's User Interface](#step-6-design-your-apps-user-interface)
    - [Step 7: Configure Microflows](#step-7-configure-microflows)
    - [Step 8: Test Your App](#step-8-test-your-app)
    - [Step 9: Deploy Your App](#step-9-deploy-your-app)
    - [Step 10: Iterate and Improve](#step-10-iterate-and-improve)
  - [Integrate Mendix UI apps and REST APIs](#integrate-mendix-ui-apps-and-rest-apis)
    - [Step 1: Define the REST Integration](#step-1-define-the-rest-integration)
    - [Step 2: Handle Response](#step-2-handle-response)
    - [Step 3: Implement UI Interaction](#step-3-implement-ui-interaction)
    - [Step 4: Test and Debug](#step-4-test-and-debug)
    - [Step 5: Deploy and Monitor](#step-5-deploy-and-monitor)
    - [Tips](#tips)
  - [Integrate Mendix UI apps with PostgreSQL](#integrate-mendix-ui-apps-with-postgresql)
    - [Step 1: Set Up a PostgreSQL Database](#step-1-set-up-a-postgresql-database)
    - [Step 2: Configure Database Connection in Mendix](#step-2-configure-database-connection-in-mendix)
    - [Step 3: Define Entities](#step-3-define-entities)
    - [Step 4: Retrieve Data](#step-4-retrieve-data)
    - [Step 5: Manipulate Data](#step-5-manipulate-data)
    - [Step 6: Test Your App](#step-6-test-your-app)
    - [Step 7: Deploy Your App](#step-7-deploy-your-app)
    - [Tips](#tips-1)
  - [Integrate Mendix UI apps with AWS](#integrate-mendix-ui-apps-with-aws)
    - [Step 1: Set Up a Mendix Account](#step-1-set-up-a-mendix-account)
    - [Step 2: Create a Mendix App](#step-2-create-a-mendix-app)
    - [Step 3: Configure AWS Services](#step-3-configure-aws-services)
    - [Step 4: Connect Mendix App to AWS](#step-4-connect-mendix-app-to-aws)
    - [Step 5: Deploy on AWS Elastic Beanstalk](#step-5-deploy-on-aws-elastic-beanstalk)
    - [Step 6: Configure Domain and SSL (Optional)](#step-6-configure-domain-and-ssl-optional)
    - [Step 7: Test and Monitor](#step-7-test-and-monitor)
    - [Tips](#tips-2)
  - [How to DevOps Mendix apps?](#how-to-devops-mendix-apps)
    - [1. **Version Control:**](#1-version-control)
    - [2. **Continuous Integration (CI):**](#2-continuous-integration-ci)
    - [3. **Automated Testing:**](#3-automated-testing)
    - [4. **Deployment Automation:**](#4-deployment-automation)
    - [5. **Environment Management:**](#5-environment-management)
    - [6. **Infrastructure as Code (IaC):**](#6-infrastructure-as-code-iac)
    - [7. **Collaboration and Communication:**](#7-collaboration-and-communication)
    - [8. **Monitoring and Logging:**](#8-monitoring-and-logging)
    - [9. **Security Considerations:**](#9-security-considerations)
    - [10. **Continuous Delivery (CD) and Continuous Deployment (CD):**](#10-continuous-delivery-cd-and-continuous-deployment-cd)
    - [11. **Feedback Loops:**](#11-feedback-loops)
    - [12. **Documentation:**](#12-documentation)
    - [13. **Scalability and Performance:**](#13-scalability-and-performance)
    - [14. **Training and Skill Development:**](#14-training-and-skill-development)
    - [15. **Compliance and Governance:**](#15-compliance-and-governance)
  - [Build a pluggable Mendix widget](#build-a-pluggable-mendix-widget)
    - [Prerequisites](#prerequisites)
    - [Steps](#steps)
      - [1. **Create a New Mendix Widget Project:**](#1-create-a-new-mendix-widget-project)
      - [2. **Understand the Widget Structure:**](#2-understand-the-widget-structure)
      - [3. **Edit the Widget Files:**](#3-edit-the-widget-files)
      - [4. **Build and Test the Widget Locally:**](#4-build-and-test-the-widget-locally)
      - [5. **Documentation and Testing:**](#5-documentation-and-testing)
      - [6. **Publish the Widget:**](#6-publish-the-widget)
  - [Certificate](#certificate)
    - [Free "Mendix Rapid Develper" test](#free-mendix-rapid-develper-test)

## Lectures

### (Optional) Big issues for long time

- Documents always behind and incompatiable the latest Studio Pro release
- Big problems on syncing the local Studio Pro and Web UI "My Apps"

### (Optional) Personal feelings about Mendix and Low Code

### Mendix Version Selector

Install multiple versions of Mendix Studio Pro and select/switch one of them

- v10.6.1 (Release date: January 4, 2024)
- v9.24.13 (Release date: December 27, 2023)

### Mendix Quickstart

Mendix Studio Pro is a low-code development environment designed to help you create applications quickly and with minimal coding. Here's a quick start guide to get you going:

#### Step 1: Download and Install Mendix Studio Pro

1. Visit the Mendix website to download the latest version of Mendix Studio Pro.
2. Run the installer and follow the on-screen instructions to install Mendix Studio Pro on your machine.

#### Step 2: Sign Up for a Mendix Account

1. If you don't have a Mendix account, sign up for one on the Mendix website.
2. Use your Mendix account credentials to log in to Mendix Studio Pro.

#### Step 3: Create a New Mendix App

1. Open Mendix Studio Pro.
2. Click on the "New App" button or choose "File" > "New" > "App" from the menu.

#### Step 4: Define Your App

1. Provide a name and description for your app.
2. Choose the appropriate starting point for your app (e.g., a blank app, app from a template, or import an existing app).
3. Click "Create" to generate your new Mendix app.

#### Step 5: Model Your Data

1. In Mendix Studio Pro, you work with a visual modeling language. Start by defining your data model.
2. Go to the "Domain Model" section, and define entities, attributes, and associations.

#### Step 6: Design Your App's User Interface

1. Navigate to the "Pages" section to design your app's user interface.
2. Drag and drop widgets onto your pages to create forms, lists, and other UI elements.
3. Use the "Layout" tab to organize and style your pages.

#### Step 7: Configure Microflows

1. Microflows are visual workflows that define the logic of your app. Go to the "Microflows" section to create and configure microflows.
2. Connect microflows to buttons, events, or other triggers to define the behavior of your app.

#### Step 8: Test Your App

1. Use the built-in preview functionality to test your app locally.
2. Check for errors or unexpected behavior and make adjustments as needed.

#### Step 9: Deploy Your App

1. Once you're satisfied with your app, you can deploy it to the Mendix Cloud or another hosting environment.
2. Follow the deployment wizard to configure deployment settings and publish your app.

#### Step 10: Iterate and Improve

1. Mendix Studio Pro supports an iterative development process. Make changes, test, and deploy updates as needed.
2. Use the collaboration features to work on projects with a team if applicable.

For more detailed information and tutorials, refer to the official Mendix documentation available on the Mendix website. The documentation provides in-depth guidance on various aspects of Mendix app development.

### Integrate Mendix UI apps and REST APIs

To use a REST API with Mendix UI, you can follow these general steps. In Mendix, you typically work with microflows and nanoflows to integrate external services like REST APIs into your application.

#### Step 1: Define the REST Integration

1. **Create a Module:**
   - In your Mendix app, create a new module or navigate to an existing module where you want to integrate the REST API.

2. **Create a Microflow or Nanoflow:**
   - Create a new microflow or nanoflow to handle the integration logic.

3. **Add REST Call Action:**
   - Drag the "Call REST Service" action from the Toolbox onto your microflow/nanoflow.

4. **Configure REST Call:**
   - In the properties of the "Call REST Service" action, configure the REST service by specifying the URL, method (GET, POST, etc.), and any necessary headers or parameters.

#### Step 2: Handle Response

1. **Add Activities:**
   - After the REST call, add activities to handle the response. This might include parsing the JSON response, updating entities, or triggering additional logic.

2. **Use Results in UI:**
   - If you want to display the results in the Mendix UI, you can update widgets, entities, or variables in your microflow/nanoflow.

#### Step 3: Implement UI Interaction

1. **Create UI Elements:**
   - In the Mendix Studio Pro, design your UI by adding buttons, input fields, or other elements that will trigger the REST API call.

2. **Configure Events:**
   - Configure events (like button clicks) to trigger the microflow/nanoflow that contains the REST API call.

#### Step 4: Test and Debug

1. **Preview the App:**
   - Use the preview functionality to test your app locally. This allows you to see how the REST API integration behaves in the Mendix UI.

2. **Debugging:**
   - Use the debugging features in Mendix Studio Pro to troubleshoot and fix any issues that may arise during the integration.

#### Step 5: Deploy and Monitor

1. **Deploy the App:**
   - Once you're satisfied with the integration, deploy your Mendix app to the desired environment.

2. **Monitor and Maintain:**
   - Keep an eye on the integration to ensure it continues to work correctly. If there are changes to the external API, you may need to update your Mendix app accordingly.

#### Tips

- **Authentication:**
  - If the REST API requires authentication, you may need to configure this in the headers or parameters of the REST call action.

- **Error Handling:**
  - Implement error-handling mechanisms in your microflow/nanoflow to manage situations where the REST API call fails or returns an error.

- **Documentation:**
  - Refer to the documentation of the REST API you are integrating with for specific details on endpoints, parameters, and expected responses.

For detailed information and examples, refer to the official Mendix documentation and community resources.

### Integrate Mendix UI apps with PostgreSQL

Integrating a Mendix UI app with a PostgreSQL database involves several steps, including configuring the database connection, defining entities in Mendix, and creating microflows for data retrieval and manipulation. Here is a step-by-step guide:

#### Step 1: Set Up a PostgreSQL Database

1. **Install PostgreSQL:**
   - Install PostgreSQL on a server or a local machine where your database will reside.

2. **Create a Database:**
   - Create a new PostgreSQL database and set up the necessary tables according to your application's data model.

3. **Configure Database Connection:**
   - Note down the database connection details, including the hostname, port, database name, username, and password.

#### Step 2: Configure Database Connection in Mendix

1. **Open Mendix Studio Pro:**
   - Open your Mendix Studio Pro project.

2. **Go to Data Hub:**
   - In the "App Explorer," go to the "Data" section.

3. **Add Database Connection:**
   - Right-click on "Database Connections" and select "Add Connection." Choose "PostgreSQL" as the database type.

4. **Configure Connection:**
   - Enter the PostgreSQL connection details you noted earlier.

#### Step 3: Define Entities

1. **Create Entities:**
   - In the "Domain Model" section, create entities that represent the tables in your PostgreSQL database.

2. **Define Attributes:**
   - Add attributes to the entities based on the columns in your database tables.

3. **Set Associations:**
   - If there are relationships between tables, define associations between the entities.

#### Step 4: Retrieve Data

1. **Create Microflows for Data Retrieval:**
   - Design microflows to retrieve data from the PostgreSQL database. Use the "Retrieve" action to query entities.

2. **Configure Retrieval:**
   - Configure the retrieval actions to specify filters, sorting, and associations as needed.

3. **Update UI Widgets:**
   - Use the retrieved data to update data grids, templates, or other widgets on your Mendix pages.

#### Step 5: Manipulate Data

1. **Create Microflows for Data Manipulation:**
   - Design microflows to handle data manipulation tasks, such as creating, updating, or deleting records in the PostgreSQL database.

2. **Use Commit and Rollback Actions:**
   - Use "Commit" actions to persist changes to the database and "Rollback" actions to discard changes if necessary.

#### Step 6: Test Your App

1. **Preview the App:**
   - Use the preview functionality in Mendix Studio Pro to test your app locally.

2. **Inspect Data:**
   - Verify that data retrieval and manipulation are working as expected.

#### Step 7: Deploy Your App

1. **Deploy to Mendix Cloud or Other Hosting:**
   - Deploy your Mendix app to the desired environment, whether it's the Mendix Cloud or another hosting provider.

#### Tips

- **Security:**
  - Ensure that your database connection details and credentials are kept secure.

- **Indexes and Performance:**
  - Consider adding indexes to your PostgreSQL tables to optimize database performance.

- **Documentation:**
  - Refer to the official Mendix documentation for detailed guidance on integrating with databases and handling data in Mendix.

This guide provides a high-level overview, and you may need to refer to the specific documentation for Mendix and PostgreSQL for more detailed instructions based on your project requirements.

### Integrate Mendix UI apps with AWS

To create a quickstart Mendix UI app with AWS (Amazon Web Services), you can follow these general steps. This assumes you want to deploy your Mendix app on AWS. Keep in mind that AWS provides various services, and the specifics of your setup may depend on your requirements.

#### Step 1: Set Up a Mendix Account

1. **Create a Mendix Account:**
   - Sign up for a Mendix account if you don't already have one.

#### Step 2: Create a Mendix App

1. **Install Mendix Studio Pro:**
   - Download and install Mendix Studio Pro on your development machine.

2. **Create a New Mendix App:**
   - Open Mendix Studio Pro, create a new app, and design your app using Mendix's low-code development environment.

#### Step 3: Configure AWS Services

1. **Create an AWS Account:**
   - Sign up for an AWS account if you don't already have one.

2. **Choose AWS Services:**
   - Identify the AWS services you need for hosting your Mendix app. Common services include Amazon RDS for the database and AWS Elastic Beanstalk for deploying Mendix apps.

3. **Set Up RDS (Relational Database Service):**
   - Create a PostgreSQL or MySQL database using Amazon RDS.

#### Step 4: Connect Mendix App to AWS

1. **Configure Database Connection in Mendix:**
   - In Mendix Studio Pro, configure the database connection to point to your AWS RDS instance.

2. **Deploy Your Mendix App:**
   - Use Mendix Studio Pro to deploy your app. Choose the deployment option that fits your AWS setup (e.g., WAR file for AWS Elastic Beanstalk).

#### Step 5: Deploy on AWS Elastic Beanstalk

1. **Set Up AWS Elastic Beanstalk Environment:**
   - Create an AWS Elastic Beanstalk environment for deploying your Mendix app.

2. **Deploy Mendix App:**
   - Deploy your Mendix app to AWS Elastic Beanstalk. This may involve packaging your app as a WAR file and configuring the necessary settings.

#### Step 6: Configure Domain and SSL (Optional)

1. **Configure Domain:**
   - If you have a custom domain, configure it to point to your AWS Elastic Beanstalk environment.

2. **Set Up SSL (Optional):**
   - If you want to secure your app with SSL, configure an SSL certificate using AWS Certificate Manager.

#### Step 7: Test and Monitor

1. **Test Your App:**
   - Access your Mendix app on AWS and perform thorough testing.

2. **Monitor and Optimize:**
   - Use AWS monitoring tools to keep an eye on your app's performance and optimize as needed.

#### Tips

- **AWS Resources:**
  - AWS provides extensive documentation for each service. Refer to the AWS documentation for specific details on setting up RDS, Elastic Beanstalk, and other services.

- **Mendix Documentation:**
  - Check the Mendix documentation for guidance on deployment and best practices.

- **Security Considerations:**
  - Ensure that your AWS resources are secured following best practices, and configure security groups and IAM roles appropriately.

This guide provides a high-level overview, and the specific steps may vary based on your app's requirements and the AWS services you choose. Always refer to the latest documentation for both Mendix and AWS for the most accurate and up-to-date information.

### How to DevOps Mendix apps?

DevOps practices in the context of Mendix applications involve integrating development and operations processes to streamline the development lifecycle, improve collaboration, and ensure efficient delivery of high-quality software. Here are some steps and best practices for implementing DevOps for Mendix apps:

#### 1. **Version Control:**

- Use a version control system (e.g., Git) to manage your Mendix application source code. This ensures that changes are tracked, and you have a history of your application's codebase.

#### 2. **Continuous Integration (CI):**

- Set up a CI pipeline to automatically build and test your Mendix application whenever changes are pushed to the version control system. This helps catch issues early in the development process.

#### 3. **Automated Testing:**

- Implement automated testing for your Mendix app. This includes unit testing, integration testing, and end-to-end testing to ensure the application's functionality remains intact with each code change.

#### 4. **Deployment Automation:**

- Automate the deployment process to move your Mendix app through different environments (e.g., development, testing, production). Tools like Jenkins, Azure DevOps, or GitLab CI/CD can be configured to deploy Mendix apps.

#### 5. **Environment Management:**

- Use environment management tools to handle configuration differences between environments. Mendix-specific tools and configurations can help manage database connections, environment-specific variables, and other settings.

#### 6. **Infrastructure as Code (IaC):**

- If you're using infrastructure components like databases, servers, or cloud services, consider adopting Infrastructure as Code principles. Tools like AWS CloudFormation or Azure Resource Manager templates can help manage and version your infrastructure.

#### 7. **Collaboration and Communication:**

- Foster collaboration between development, operations, and other stakeholders. Clear communication and collaboration tools can help ensure everyone is on the same page regarding project status, issues, and changes.

#### 8. **Monitoring and Logging:**

- Implement monitoring and logging solutions to track the performance and behavior of your Mendix app in real-time. This helps identify and address issues proactively.

#### 9. **Security Considerations:**

- Integrate security checks into your CI/CD pipeline to scan for vulnerabilities. Regularly update dependencies and address security issues promptly.

#### 10. **Continuous Delivery (CD) and Continuous Deployment (CD):**

- Aim for continuous delivery or continuous deployment to automate the release process. Continuous delivery involves automating the release to a staging environment, while continuous deployment automatically releases changes to production.

#### 11. **Feedback Loops:**

- Establish feedback loops to gather insights from users, monitor application usage, and collect feedback to continuously improve your Mendix app.

#### 12. **Documentation:**

- Maintain comprehensive documentation for your Mendix application, including deployment processes, configurations, and any customizations.

#### 13. **Scalability and Performance:**

- Plan for scalability and monitor the performance of your Mendix app. Adjust resources and configurations as needed to handle increased demand.

#### 14. **Training and Skill Development:**

- Ensure that the DevOps team members have the necessary training and skills to effectively manage Mendix applications in a DevOps environment.

#### 15. **Compliance and Governance:**

- Adhere to compliance and governance standards relevant to your industry. Ensure that your DevOps practices align with organizational policies.

DevOps practices are adaptable, and the specific tools and processes you choose may depend on your organization's needs and preferences. Regularly review and update your DevOps practices to align with the evolving requirements of your Mendix applications.

### Build a pluggable Mendix widget

Building a pluggable Mendix widget involves creating a custom widget that can be easily integrated into Mendix applications. Mendix widgets are typically developed using HTML, CSS, and JavaScript, and they are used to extend the functionality of Mendix applications. Here are the general steps to build a pluggable Mendix widget:

#### Prerequisites

1. **Mendix Studio Pro:**
   - Make sure you have Mendix Studio Pro installed on your development machine.

2. **Development Environment:**
   - Set up a development environment with a text editor or an integrated development environment (IDE) of your choice.

#### Steps

##### 1. **Create a New Mendix Widget Project:**

1. Open Mendix Studio Pro.

2. Create a new Mendix widget project:
   - Click on "Develop" in the top menu.
   - Click on "App Store" in the sidebar.
   - Click on "Create your own app store module."
   - Choose "Widget" as the module type.

3. Name your widget and choose a location for your project.

##### 2. **Understand the Widget Structure:**

1. Navigate to the project folder on your machine. The structure typically includes directories for `src` (source code), `test` (unit tests), and `ui` (Mendix Studio Pro integration).

2. Open the `src` directory, where you'll find HTML, CSS, and JavaScript files.

##### 3. **Edit the Widget Files:**

1. Open the `src` directory and edit the following files:

   - **`widgetname.xml` (Descriptor):**
     - Define the widget properties, events, and dependencies in XML format.

   - **`widgetname.js` (JavaScript):**
     - Write the JavaScript logic for your widget. You can use the Mendix JavaScript API to interact with the Mendix runtime.

   - **`widgetname.css` (CSS):**
     - Style your widget using CSS.

   - **`widgetname.html` (HTML):**
     - Design the HTML structure of your widget.

##### 4. **Build and Test the Widget Locally:**

1. Open a command line terminal in the project directory.

2. Run the following command to build your widget:

   ```bash
   npm run build
   ```

3. Import the built `.mpk` file into Mendix Studio Pro:
   - Click on "Import" in the top menu.
   - Choose the `.mpk` file from the `dist` directory.

4. Add the widget to a Mendix page and test its functionality.

##### 5. **Documentation and Testing:**

1. Provide documentation for your widget:
   - Include usage instructions, properties, and events.

2. Test your widget thoroughly:
   - Ensure it works well with different configurations and in various scenarios.

##### 6. **Publish the Widget:**

1. Once your widget is ready, you can publish it to the Mendix Marketplace:
   - Use the Mendix Developer Portal to create a new App Store item.
   - Upload your `.mpk` file and provide relevant information.

2. Publish the widget to make it available to the Mendix community.

Building a pluggable Mendix widget requires a good understanding of HTML, CSS, and JavaScript, as well as knowledge of the Mendix widget development process. Refer to the Mendix documentation for detailed information on widget development, including the JavaScript API and best practices.

### Certificate

#### Free "Mendix Rapid Develper" test
