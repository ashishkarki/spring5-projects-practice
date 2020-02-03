# Spring based application to List Countries with their GDP

We use spring, Thymeleaf and some JavaScript to build a full-stack app showing countries with their GDP.

We will use the following tools and technologies in this application:
- Spring MVC framework for implementing the MVC pattern
- The interaction with the MySQL DB will be done using the
Spring JDBC template
- The interaction with the World Bank API will be done using
RestTemplate
- The views will be created using a templating framework called
Thymeleaf
- The frontend will be driven by jQuery and Bootstrap

## First Step

The first step is to install MySQL. Next, install the sample [World DB](https://dev.mysql.com/doc/world-setup/en/world-setup-installation.html) available with MySQL to list the countries and get a detailed view to display the country information and its GDP information obtained from the [World Bank API](https://datahelpdesk.worldbank.org/knowledgebase/articles/898599-api-indicator-queries).

If you have reset your root password, refer to this great article on [how to reset MySQL root password](https://www.pixelstech.net/article/1545701135-How-to-reset-root-password-in-MySQL-8).

If resetting the password doesn't work, unfortunately you have to try uninstall mysql and installing a fresh version. The uninstallation part is a bit tricky and here is a great link showing [how to uninstall mysql completely for windows case](https://answers.microsoft.com/en-us/windows/forum/all/how-to-completely-uninstall-mysql/e90e1344-7b90-4319-8b2f-77b271ae66ed)