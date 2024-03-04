
# Automated Machine Learning Experiment on Microsoft Azure

This README file guides you through the process of setting up an Automated Machine Learning experiment using Microsoft Azure. Follow these steps to create an Azure account, set up Azure Machine Learning, configure, and test your model.

## Prerequisites

- **Microsoft Azure Account**: Ensure you have access to a Microsoft Azure account. If you do not have one, you can sign up at [Azure's website](https://azure.microsoft.com/).

## Step 1: Create a Microsoft Azure Account

If you are new to Azure:

1. Visit the [Microsoft Azure website](https://azure.microsoft.com/).
2. Click on "Start free" to sign up. You will need to provide personal information and payment details.
3. Follow the on-screen instructions to complete the account setup.

## Step 2: Access Azure Portal

Once your account is set up:

1. Go to the [Azure Portal](https://portal.azure.com/).
2. Sign in with your Microsoft Azure credentials.

## Step 3: Create a Resource for Azure Machine Learning

In the Azure Portal:

1. Click on “**Create a Resource**” in the top-left corner.
2. In the search bar, type “**Azure Machine Learning**” and select it from the dropdown menu.
3. Click on “**Create**” to start the setup process.

## Step 4: Set Up Azure Machine Learning

Follow these steps to create your Azure Machine Learning workspace:

1. **Subscription**: Select the Azure subscription in which to create the resource.
2. **Resource Group**: Create a new resource group or select an existing one. A resource group is a container that holds related resources for an Azure solution.
3. **Workspace Name**: Enter a name for your workspace.
4. **Region**: Choose the region closest to your users to minimize latency.
5. **Review and Create**: Review your selections and click “Create”.

Wait for the deployment to complete.

## Step 5: Configure Your Machine Learning Model

After creating your workspace:

1. Go to your new workspace in the Azure portal.
2. Navigate to the “**Automated ML**” section.
3. Click on “**New Automated ML run**”.
4. Follow the instructions to configure your model:
   - **Select Dataset**: Upload your data or select one of Azure's sample datasets.
   - **Configure Run**: Choose your target column, training task, and other model settings.
   - **Additional Settings**: Configure compute, exit criteria, and concurrency.

## Step 6: Train and Test the Model

1. **Train the Model**: Click on “**Run**” to start the training process.
2. Monitor the training process and view the results once it's completed.
3. **Evaluate the Model**: Check the accuracy and performance metrics.
4. **Test the Model**: Use test data or Azure's in-built testing features to evaluate the model's predictions.

## Step 7: Deployment (Optional)

If satisfied with the model:

1. Navigate to the “**Models**” section in your workspace.
2. Select the model you wish to deploy.
3. Follow Azure's guidelines for deploying the model as a web service.

## Additional Resources

- **Azure ML Documentation**: For detailed guidance and advanced configurations, refer to the [Azure Machine Learning documentation](https://docs.microsoft.com/en-us/azure/machine-learning/).
