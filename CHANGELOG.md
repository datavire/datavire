# v1.10.0 (2025-03-05)

### Features
	* Provided the options to customize the Date and Time formats based on Orgs.
	* Added the feature to create the custom report variables

### Bug Fixes
	* Fixed the issue while connecting SMTP server with no authentication

### Minor Changes
	* Added few default report variables
	* Added the support for Grafana upto v11.5.x
	* Added the support for Kibana upto v8.17.x

# v1.9.1 (2025-01-06)

### Minor Changes
	* Added the support for Grafana upto v11.4.0

# v1.9.0 (2025-01-04)

### Features
	* Added the feature to distribute reports via "Slack" app
	* Added the feature to distribute reports via "WhatsApp"
	* Added the feature to distribute reports via "MS Teams" app
	* Added the ability to change the Grafana theme for the report in the report builder

# v1.8.10 (2024-11-19)

### Bug Fixes
	* Fixed the column issue with Grafana excel reports

# v1.8.9 (2024-11-06)

### Features
	* Added the support to upload multiple images at same time in report builder
	* Added the support to fetch and generate panels inside dashboard row for Grafana

### Bug Fixes
	* Fixed the issue while resetting the report builder after dashboard change

### Minor Changes
	* Improved the stability throughout the application while loading images

# v1.8.8 (2024-10-20)

### Features
	* Added support to generate excel and csv reports with multi series(query) panels

# v1.8.7 (2024-10-16)

### Bug Fixes
	* Fixed the issue in delivering report with No Auth distribution channels 

# v1.8.6 (2024-10-09)

### Bug Fixes
	* Fixed the issue while connecting Grafana with API key

# v1.8.5 (2024-09-02)

### Minor Changes
	* Added support for Grafana upto 11.3.x
	* Added support for Kibana upto 8.15.x

# v1.8.4 (2024-08-20)

### Bug Fixes
	* Fixed the issue with offline subscription activation

# v1.8.3 (2024-08-13)

### Bug Fixes
	* Fixed the issue while applying template with all pages

### Minor Changes
	* Added the support for Grafana upto v11.2.x

# v1.8.2 (2024-07-26)

### Minor Changes
	* Added support for Grafana v7.1.5 for advanced report

# v1.8.1 (2024-07-16)

### Bug Fixes
	* Fixed the minor design issue in Grafana panels

# v1.8.0 (2024-07-09)

### Features
	* Added an option to apply the transparency in images, elements, texts and panels
	* Added an option to flip the image vertically and horizontally
	* Added an option to customize the border colors and size for the elements
	* Extended the option of bringing element front and back to panels and texts
	* Added an ability to retain the design changes when changing the dashboard or datasource in advanced reports
	* Added an option to apply the all the pages of the templates
	* Added the new feature to select multiple panels and add it to the report with desired layout and page

### Minor Changes
	* Updated the icons all over the application
	* Updated the default Grafana and Kibana panel colors
	* Removed the ability to edit the default templates
	* Panels will be added in the report based on the it's original size in dashboard
	* Added the support for Grafana 11.1.0 and Kibana 8.14.2

# v1.7.1 (2024-06-11)

### Bug Fixes
	* Fixed the PDF report generation issue for Grafana 9.5 and below

### Minor Changes
	* Added a support for Kibana upto v8.14.0

# v1.7.0 (2024-06-04)

### Features
	* Added the ability to upload user profile picture
	* Added the featture to create and manage multiple organizations
	* Added the feature to add and manage users based on organizations
	* Added the feature to assign the role for users
	* Added the ability to switch across  organizations

### Minor Changes
	* Added a support for Grafana upto v11.0.0
	* Timezone and Weekdays preferences moved to organization level
	* Change password screen merged with user profile

# v1.6.2 (2024-05-13)

### Features
	* Added an option to move the elements & images to bring front and send to back

### Bug Fixes
	* Fixed the Cross-Browser drag and drop lagging issue
	* Fixed the Cross-Browser panels fit to layout issue
	* Fixed the Cross-Browser texts wrapping issue in report builder
	* Fixed the listing issue in distribution channels

### Minor Changes
	* Added additional layouts in the report builder
	* Improved the overall design stability 

# v1.6.1 (2024-04-30)

### Bug Fixes
	* Fixed the issue while dnd with layouts in report builder
	* Fixed the texts overriding issue in report builder
	* Fixed the data merging issue in excel formatted reports

### Minor Changes
	* Added an option to format/unformat the excel reports
	* Added a ability to scale the table type panels for Grafana

# v1.6.0 (2024-04-25)

### Features
	* Added the dynamic pagination feature for the listing pages (reports etc)
	* Added the feature to mark tags in the reports
	* Added the feature to duplicate an existing report

### Minor Changes
	* Updated the batch script for windows installation

# v1.5.3 (2024-04-22)

### Minor Changes
	* Added a support for Kibana upto v8.13.2
	* Added a support for Grafana upto v10.4.2
	* Added the ability to skip self-signed tls verification

# v1.5.0 (2024-03-18)

### Features
	* Added the new feature to create the report templates
	* Added a feature to create an advanced report with report templates
	* Added a support to upload and use brand fonts in reports
	* Added a support for and extensive customization
	* Added a support for Grafana 10.4
	* Added a support for Kibana 8.12

# v1.4.1 (2024-02-01)

### Bug Fixes
	* Fixed the report preview alignment issue for large screens

### Minor Changes
	* Improved the PDF reports perfection
	* Enabled the report preview for landscape reports

# v1.4.0 (2024-01-26)

### Features
	* Added the Grafana support till 10.3.1
	* Added the Kibana support till 8.12.0

### Bug Fixes
	* Fixed the error when creating a distribution channel without auth

### Minor Changes
	* Added a screen to change default password when login
	* Improved the logging mechanism

# v1.3.0 (2024-01-09)

### Features
	* Added the support for "Kibana Saved Search" with Excel and CSV 
	* Implemented the smooth user interface

### Bug Fixes
	* Fixed the issue with change password
	* Fixed the issue with save and send test report

### Minor Changes
	* Improved the stability of PDF generation for different layouts
	* Added note for kibana index for latest version

# v1.2.0 (2023-12-27)

### Features
	* Added reporting support for Kibana stack

### Minor Changes
	* Added support for Grafana 10.2.3

# v1.1.1 (2023-11-08)

### Features
	* Added the support for Grafana 10.2

### Minor Changes
	* Improved the stability of generation messages
	* Log files changed as zip format
	* CSV reports changed as zip format

# v1.1.0 (2023-10-13)

### Features
	* Added the support configure the weekdays based on timezone
	* Added the support to schedule report only on weekdays

### Bug Fixes
	* Fixed the issue in persist server timezone

### Minor Changes
	* Added timezone in Excel & CSV format report
	* Improvement on application loader stability
	* Added the font formatting in mail templates

# v1.0.2 (2023-10-07)

### Bug Fixes
	* Fixed the rendering issue with Grafana 9.5.x

### Minor Changes
	* Added the theme into the excel formatting

# v1.0.1 (2023-10-03)

### Minor Changes
	* Added support for Grafana 10.x

# v1.0.0 (2023-10-01)

### Features
	* Stable release with branded features

