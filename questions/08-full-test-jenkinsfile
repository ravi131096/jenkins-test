# 8. Configuring Jenkins for the Simple Java App

## Step 1: Install Jenkins Locally
Check **01-local-configuration**.

## Step 2: Install Required Plugins
1. Go to **Manage Jenkins** > **Manage Plugins**.
2. Install the following plugins if they are not already installed:
   - **Git Plugin**: For pulling code from Git repositories.
   - **Maven Integration Plugin**: If you plan to use Maven for building the project.

## Step 3: Create a New Jenkins Job

## Step 4: Configure Source Code Management
## Repository: https://github.com/kindredgroup/basic-test-project.git
  
## Step 5: Add Build and run stages
- Create a declarative pipeline
-- Use docker image: maven:3.8.1-openjdk-11-slim
- Sample commands
-- Build: 'mvn clean package'
-- Run: 'java -cp target/simple-java-app-1.0-SNAPSHOT.jar com.example.App'

### Tip: Install maven on the jenkins container or find an agent with maven available