# [Material Dashboard PRO React Asp.net](https://www.creative-tim.com/live/material-dashboard-pro-react-asp-net) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fcreative-tim.com%2Flive%2Fmaterial-dashboard-pro-react-aspnet%2F%23%2Fdashboard&text=Material%20Dashboard%20PRO%20React%20Asp.net%20-%20Premium%20Asp.net%20Admin%20Template&original_referer=https%3A%2F%2Fdemos.creative-tim.com%2Fmaterial-dashboard-pro-react-aspnet%2F%3F_ga%3D2.234372891.44370326.1533641128-1803433978.1528781151&via=creativetim&hashtags=react%2Caspnet)



![version](https://img.shields.io/badge/version-1.0.0-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/ct-material-dashboard-pro-react-aspnet.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-material-dashboard-pro-react-aspnet/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/ct-material-dashboard-pro-react-aspnet.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-material-dashboard-pro-react-aspnet/issues-react?q=is%3Aissue+is%3Aclosed)

![Product Gif](./src/assets/github/material-dashboard-pro-react.gif)

Material Dashboard PRO React Asp.net is a Premium Material-UI Admin created using [create-react-app](https://github.com/facebook/create-react-app) with a fresh, new design inspired by Google's Material Design. We are very excited to introduce our take on the material concepts through an easy to use and beautiful set of components. Material Dashboard PRO React Asp.net was built over the popular Material-UI framework.

Material Dashboard PRO React Asp.net makes use of light, surface and movement. The general layout resembles sheets of paper following multiple different layers, so that the depth and order is obvious. The navigation stays mainly on the left sidebar and the content is on the right.

Material Dashboard PRO React Asp.net comes with 7 color filter choices for the links of the Sidebar (blue, green, orange, red, purple, rose, white), 3 filter color choices for background of the Sidebar (white, blue`, black), an option to have a background image on the Sidebar and 6 color filter choices the card headers (blue, green, orange, red, purple, rose).

Material Dashboard PRO React Asp.net uses a framework built by our friend [Olivier - Material-UI](https://github.com/mui-org/material-ui), who did an amazing job creating the backbone for the material effects, animations, ripples and transitions. Big thanks to his team for the effort and forward thinking they put into it.

#### Special thanks
During the development of this dashboard, we have used many existing resources from awesome developers. We want to thank them for providing their tools open source:
+ [Perfect-scrollbar](https://github.com/utatti/perfect-scrollbar) for the slim and beautiful scrollbars.
+ [React-chartist](https://github.com/fraserxu/react-chartist) for the wonderful charts.
+ [React-datetime](https://github.com/YouCanBookMe/react-datetime) for the easy to use date and time pickers.
+ [React-big-calendar](https://github.com/intljusticemission/react-big-calendar) for the a wonderful calendar.
+ [React-bootstrap-sweetalert](https://github.com/djorg83/react-bootstrap-sweetalert) for the wonderful alerts.
+ [React-google-maps](https://github.com/tomchentw/react-google-maps) for the nice and easy to use map components.
+ [React-jvectormap](https://github.com/kadoshms/react-jvectormap) for the nice vector map components.
+ [React-nouislider](https://github.com/algolia/react-nouislider) for the nice and clean slider.
+ [React-tables](https://react-table.js.org/#/story/simple-table) for the nice and clean slider.
+ [React-tagsinput](https://github.com/olahol/react-tagsinput) for the easy and beatiful to use tags components.

Let us know your thoughts below. And good luck with development!

## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Usage](#usage)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)


## Versions

[<img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/aspnet-logo.jpg" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro-react-aspnet)


| Asp.net | 
| --- | 
| [![Material Dashboard Pro React Asp.net](https://s3.amazonaws.com/creativetim_bucket/products/399/original/opt_mdp_react_aspnet_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-pro-react-aspnet)|

## Demo

- [Start page](https://www.creative-tim.com/live/material-dashboard-pro-react-asp-net)


## Quick start

Quick start options:

- Buy from [Creative Tim](https://www.creative-tim.com/product/material-dashboard-pro-react-asp-net)
- Download and install [Docker]("https://docs.docker.com/desktop/")
- From the project root folder run `docker-compose up --build`. Note that the first time you run this the images will build.
- Once docker-compose has finished, you will find the projects on the following URLs:
[Dashboard](http://localhost:3002/admin/dashboard)
[Identity Server](https://localhost:5001/.well-known/openid-configuration)
[Post API](https://localhost:3003) - Access requires authentication but you can check if the application is available by navigating to https://localhost:3003/health


## Usage
You now have 3 applications running consisting of a React front end, application an Identity Server (IDS) based on C#/.NET  Core and a C#/.NET Core API project. The implantation of Identity Server follow the resource owner password flow but can be modified to support others.

The integration gives you 3 features for identity management:
1. Login. The IDS has 3 default logins to get you started along with their default permissions (role):
	Username: alice	Password: Pass123$ Role: admin
    Username: fred	Password: Pass123$ Role: creator
	Username: bob	Password: Pass123$ Role: member

    **NOTE:** Any new user will automatically be assigned to the member role

2. Register. This registers a new user in IDS

3. User Profile. Update profile and change password. Note: You need to be logged in to view this page.

If you wish to change any of the settings around authentications, please refer to the following files:
- \React\src\services\oauth.js
- \IdentityServer\Config.cs
- \IdentityServer\Startup.cs
- \IdentityServer\Quickstart\Account\AccountOptions.cs

You can find documentation  on IDS [here](https://identityserver.io/)


## Documentation
The documentation for the Material Dashboard Pro React Aspnet is hosted at our [website](https://demos.creative-tim.com/material-dashboard-pro-react/#/documentation/tutorial).


## File Structure

Within the download you'll find the following directories and files:

```
material-dashboard-pro-react-aspnet
.
├── API
│   ├── API.csproj
│   ├── Controllers
│   │   └── PostsController.cs
│   ├── DataSchema
│   │   ├── DataContext.cs
│   │   ├── Extensions
│   │   │   └── ModelBuilderExtensions.cs
│   │   ├── ModelConfiguration
│   │   │   └── PostConfiguration.cs
│   │   └── Post.cs
│   ├── Dockerfile
│   ├── Posts.db
│   ├── Program.cs
│   ├── Properties
│   │   └── launchSettings.json
│   ├── Repositories
│   │   ├── BaseRepository.cs
│   │   ├── IPostRepository.cs
│   │   ├── IRepository.cs
│   │   └── PostRepository.cs
│   ├── Services
│   │   ├── IPostService.cs
│   │   └── PostService.cs
│   ├── Startup.cs
│   └── appsettings.json
├── CreativeTim.sln
├── IdentityServer
│   ├── Config.cs
│   ├── Data
│   │   ├── ApplicationDbContext.cs
│   │   └── Migrations
│   │       ├── 20180109192453_CreateIdentitySchema.Designer.cs
│   │       ├── 20180109192453_CreateIdentitySchema.cs
│   │       └── ApplicationDbContextModelSnapshot.cs
│   ├── Dockerfile
│   ├── Helpers
│   │   ├── ProfileWithRoleIdentityResource.cs
│   │   └── X509Helper.cs
│   ├── IdentityServer.csproj
│   ├── Models
│   │   ├── AddRoleModel.cs
│   │   └── ApplicationUser.cs
│   ├── Program.cs
│   ├── Properties
│   │   └── launchSettings.json
│   ├── Quickstart
│   │   ├── Account
│   │   │   ├── AccountController.cs
│   │   │   ├── AccountOptions.cs
│   │   │   ├── ExternalController.cs
│   │   │   ├── ExternalProvider.cs
│   │   │   ├── LoggedOutViewModel.cs
│   │   │   ├── LoginInputModel.cs
│   │   │   ├── LoginViewModel.cs
│   │   │   ├── LogoutInputModel.cs
│   │   │   ├── LogoutViewModel.cs
│   │   │   ├── PasswordController.cs
│   │   │   ├── ProfileController.cs
│   │   │   ├── RedirectViewModel.cs
│   │   │   ├── RegisterController.cs
│   │   │   ├── RegisterViewModel.cs
│   │   │   ├── RoleController.cs
│   │   │   ├── UpdatePasswordModel.cs
│   │   │   ├── UpdateProfileModel.cs
│   │   │   └── UserController.cs
│   │   ├── Consent
│   │   │   ├── ConsentController.cs
│   │   │   ├── ConsentInputModel.cs
│   │   │   ├── ConsentOptions.cs
│   │   │   ├── ConsentViewModel.cs
│   │   │   ├── ProcessConsentResult.cs
│   │   │   └── ScopeViewModel.cs
│   │   ├── Device
│   │   │   ├── DeviceAuthorizationInputModel.cs
│   │   │   ├── DeviceAuthorizationViewModel.cs
│   │   │   └── DeviceController.cs
│   │   ├── Diagnostics
│   │   │   ├── DiagnosticsController.cs
│   │   │   └── DiagnosticsViewModel.cs
│   │   ├── Extensions.cs
│   │   ├── Grants
│   │   │   ├── GrantsController.cs
│   │   │   └── GrantsViewModel.cs
│   │   ├── Home
│   │   │   ├── ErrorViewModel.cs
│   │   │   └── HomeController.cs
│   │   ├── SecurityHeadersAttribute.cs
│   │   └── TestUsers.cs
│   ├── SeedData.cs
│   ├── Startup.cs
│   ├── Views
│   │   ├── Account
│   │   │   ├── AccessDenied.cshtml
│   │   │   ├── LoggedOut.cshtml
│   │   │   ├── Login.cshtml
│   │   │   └── Logout.cshtml
│   │   ├── Consent
│   │   │   └── Index.cshtml
│   │   ├── Device
│   │   │   ├── Success.cshtml
│   │   │   ├── UserCodeCapture.cshtml
│   │   │   └── UserCodeConfirmation.cshtml
│   │   ├── Diagnostics
│   │   │   └── Index.cshtml
│   │   ├── Grants
│   │   │   └── Index.cshtml
│   │   ├── Home
│   │   │   └── Index.cshtml
│   │   ├── Shared
│   │   │   ├── Error.cshtml
│   │   │   ├── Redirect.cshtml
│   │   │   ├── _Layout.cshtml
│   │   │   ├── _Nav.cshtml
│   │   │   ├── _ScopeListItem.cshtml
│   │   │   └── _ValidationSummary.cshtml
│   │   ├── _ViewImports.cshtml
│   │   └── _ViewStart.cshtml
│   ├── appsettings.json
│   ├── tempkey.jwk
│   ├── updateUI.ps1
│   └── wwwroot
│       ├── css
│       │   └── site.scss
│       ├── favicon.ico
│       ├── js
│       │   ├── signin-redirect.js
│       │   └── signout-redirect.js
│       └── lib
│           ├── bootstrap
│           │   ├── README.md
│           │   ├── dist
│           │   │   ├── css
│           │   │   │   ├── bootstrap-grid.css.map
│           │   │   │   ├── bootstrap-grid.min.css.map
│           │   │   │   ├── bootstrap-reboot.css.map
│           │   │   │   ├── bootstrap-reboot.min.css.map
│           │   │   │   ├── bootstrap.css.map
│           │   │   │   └── bootstrap.min.css.map
│           │   │   └── js
│           │   │       ├── bootstrap.bundle.js
│           │   │       ├── bootstrap.bundle.js.map
│           │   │       ├── bootstrap.bundle.min.js
│           │   │       ├── bootstrap.bundle.min.js.map
│           │   │       ├── bootstrap.js
│           │   │       ├── bootstrap.js.map
│           │   │       ├── bootstrap.min.js
│           │   │       └── bootstrap.min.js.map
│           │   └── scss
│           │       ├── _alert.scss
│           │       ├── _badge.scss
│           │       ├── _breadcrumb.scss
│           │       ├── _button-group.scss
│           │       ├── _buttons.scss
│           │       ├── _card.scss
│           │       ├── _carousel.scss
│           │       ├── _close.scss
│           │       ├── _code.scss
│           │       ├── _custom-forms.scss
│           │       ├── _dropdown.scss
│           │       ├── _forms.scss
│           │       ├── _functions.scss
│           │       ├── _grid.scss
│           │       ├── _images.scss
│           │       ├── _input-group.scss
│           │       ├── _jumbotron.scss
│           │       ├── _list-group.scss
│           │       ├── _media.scss
│           │       ├── _mixins.scss
│           │       ├── _modal.scss
│           │       ├── _nav.scss
│           │       ├── _navbar.scss
│           │       ├── _pagination.scss
│           │       ├── _popover.scss
│           │       ├── _print.scss
│           │       ├── _progress.scss
│           │       ├── _reboot.scss
│           │       ├── _root.scss
│           │       ├── _spinners.scss
│           │       ├── _tables.scss
│           │       ├── _toasts.scss
│           │       ├── _tooltip.scss
│           │       ├── _transitions.scss
│           │       ├── _type.scss
│           │       ├── _utilities.scss
│           │       ├── _variables.scss
│           │       ├── bootstrap-grid.scss
│           │       ├── bootstrap-reboot.scss
│           │       ├── bootstrap.scss
│           │       ├── mixins
│           │       │   ├── _alert.scss
│           │       │   ├── _background-variant.scss
│           │       │   ├── _badge.scss
│           │       │   ├── _border-radius.scss
│           │       │   ├── _box-shadow.scss
│           │       │   ├── _breakpoints.scss
│           │       │   ├── _buttons.scss
│           │       │   ├── _caret.scss
│           │       │   ├── _clearfix.scss
│           │       │   ├── _deprecate.scss
│           │       │   ├── _float.scss
│           │       │   ├── _forms.scss
│           │       │   ├── _gradients.scss
│           │       │   ├── _grid-framework.scss
│           │       │   ├── _grid.scss
│           │       │   ├── _hover.scss
│           │       │   ├── _image.scss
│           │       │   ├── _list-group.scss
│           │       │   ├── _lists.scss
│           │       │   ├── _nav-divider.scss
│           │       │   ├── _pagination.scss
│           │       │   ├── _reset-text.scss
│           │       │   ├── _resize.scss
│           │       │   ├── _screen-reader.scss
│           │       │   ├── _size.scss
│           │       │   ├── _table-row.scss
│           │       │   ├── _text-emphasis.scss
│           │       │   ├── _text-hide.scss
│           │       │   ├── _text-truncate.scss
│           │       │   ├── _transition.scss
│           │       │   └── _visibility.scss
│           │       ├── utilities
│           │       │   ├── _align.scss
│           │       │   ├── _background.scss
│           │       │   ├── _borders.scss
│           │       │   ├── _clearfix.scss
│           │       │   ├── _display.scss
│           │       │   ├── _embed.scss
│           │       │   ├── _flex.scss
│           │       │   ├── _float.scss
│           │       │   ├── _overflow.scss
│           │       │   ├── _position.scss
│           │       │   ├── _screenreaders.scss
│           │       │   ├── _shadows.scss
│           │       │   ├── _sizing.scss
│           │       │   ├── _spacing.scss
│           │       │   ├── _stretched-link.scss
│           │       │   ├── _text.scss
│           │       │   └── _visibility.scss
│           │       └── vendor
│           │           └── _rfs.scss
│           └── jquery
│               ├── LICENSE.txt
│               ├── README.md
│               └── dist
│                   ├── jquery.js
│                   ├── jquery.min.js
│                   ├── jquery.min.map
│                   ├── jquery.slim.js
│                   ├── jquery.slim.min.js
│                   └── jquery.slim.min.map
├── README.md
├── React
│   ├── CHANGELOG.md
│   ├── Dockerfile
│   ├── ISSUE_TEMPLATE.md
│   ├── React.njsproj
│   ├── documentation
│   │   ├── assets
│   │   │   ├── css
│   │   │   ├── img
│   │   │   │   └── faces
│   │   │   └── js
│   │   │       ├── bootstrap.min.js
│   │   │       └── jquery-3.2.1.min.js
│   │   └── tutorial-components.html
│   ├── gulpfile.js
│   ├── jsconfig.json
│   ├── package.json
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   └── manifest.json
│   └── src
│       ├── App.js
│       ├── actions
│       │   ├── authActions.js
│       │   └── types.js
│       ├── assets
│       │   ├── css
│       │   │   └── material-dashboard-pro-react.css.map
│       │   ├── github
│       │   │   └── material-dashboard-pro-react.gif
│       │   ├── img
│       │   │   ├── faces
│       │   │   ├── flags
│       │   │   ├── logo-white.svg
│       │   │   └── logo.svg
│       │   ├── jss
│       │   │   ├── material-dashboard-pro-react
│       │   │   │   ├── buttonGroupStyle.js
│       │   │   │   ├── cardImagesStyles.js
│       │   │   │   ├── components
│       │   │   │   │   ├── accordionStyle.js
│       │   │   │   │   ├── adminNavbarLinksStyle.js
│       │   │   │   │   ├── adminNavbarStyle.js
│       │   │   │   │   ├── authNavbarStyle.js
│       │   │   │   │   ├── badgeStyle.js
│       │   │   │   │   ├── buttonStyle.js
│       │   │   │   │   ├── cardAvatarStyle.js
│       │   │   │   │   ├── cardBodyStyle.js
│       │   │   │   │   ├── cardFooterStyle.js
│       │   │   │   │   ├── cardHeaderStyle.js
│       │   │   │   │   ├── cardIconStyle.js
│       │   │   │   │   ├── cardStyle.js
│       │   │   │   │   ├── cardTextStyle.js
│       │   │   │   │   ├── customDropdownStyle.js
│       │   │   │   │   ├── customInputStyle.js
│       │   │   │   │   ├── customLinearProgressStyle.js
│       │   │   │   │   ├── customTabsStyle.js
│       │   │   │   │   ├── footerStyle.js
│       │   │   │   │   ├── headingStyle.js
│       │   │   │   │   ├── infoStyle.js
│       │   │   │   │   ├── instructionStyle.js
│       │   │   │   │   ├── navPillsStyle.js
│       │   │   │   │   ├── paginationStyle.js
│       │   │   │   │   ├── sidebarStyle.js
│       │   │   │   │   ├── snackbarContentStyle.js
│       │   │   │   │   ├── tableStyle.js
│       │   │   │   │   ├── tasksStyle.js
│       │   │   │   │   ├── timelineStyle.js
│       │   │   │   │   ├── typographyStyle.js
│       │   │   │   │   └── wizardStyle.js
│       │   │   │   ├── customCheckboxRadioSwitch.js
│       │   │   │   ├── customSelectStyle.js
│       │   │   │   ├── hoverCardStyle.js
│       │   │   │   ├── layouts
│       │   │   │   │   ├── adminStyle.js
│       │   │   │   │   ├── authStyle.js
│       │   │   │   │   └── rtlStyle.js
│       │   │   │   ├── modalStyle.js
│       │   │   │   └── views
│       │   │   │       ├── buttonsStyle.js
│       │   │   │       ├── chartsStyle.js
│       │   │   │       ├── dashboardStyle.js
│       │   │   │       ├── errorPageStyles.js
│       │   │   │       ├── extendedFormsStyle.js
│       │   │   │       ├── extendedTablesStyle.js
│       │   │   │       ├── gridSystemStyle.js
│       │   │   │       ├── iconsStyle.js
│       │   │   │       ├── lockScreenPageStyle.js
│       │   │   │       ├── loginPageStyle.js
│       │   │   │       ├── notificationsStyle.js
│       │   │   │       ├── pricingPageStyle.js
│       │   │   │       ├── registerPageStyle.js
│       │   │   │       ├── regularFormsStyle.js
│       │   │   │       ├── sweetAlertStyle.js
│       │   │   │       ├── userProfileStyles.js
│       │   │   │       └── validationFormsStyle.js
│       │   │   └── material-dashboard-pro-react.js
│       │   └── scss
│       │       ├── material-dashboard-pro-react
│       │       │   ├── _colors.scss
│       │       │   ├── _fileupload.scss
│       │       │   ├── _fixed-plugin.scss
│       │       │   ├── _misc.scss
│       │       │   ├── _mixins.scss
│       │       │   ├── _shadows.scss
│       │       │   ├── _variables.scss
│       │       │   ├── mixins
│       │       │   │   ├── _chartist.scss
│       │       │   │   ├── _sidebar-color.scss
│       │       │   │   ├── _transparency.scss
│       │       │   │   └── _vendor-prefixes.scss
│       │       │   └── plugins
│       │       │       ├── _plugin-nouislider.scss
│       │       │       ├── _plugin-perfect-scrollbar.scss
│       │       │       ├── _plugin-react-big-calendar.scss
│       │       │       ├── _plugin-react-bootstrap-sweetalert.scss
│       │       │       ├── _plugin-react-chartist.scss
│       │       │       ├── _plugin-react-datetime.scss
│       │       │       ├── _plugin-react-jvectormap.scss
│       │       │       ├── _plugin-react-table.scss
│       │       │       └── _plugin-react-tagsinput.scss
│       │       └── material-dashboard-pro-react.scss
│       ├── components
│       │   ├── Accordion
│       │   │   └── Accordion.js
│       │   ├── Badge
│       │   │   └── Badge.js
│       │   ├── Card
│       │   │   ├── Card.js
│       │   │   ├── CardAvatar.js
│       │   │   ├── CardBody.js
│       │   │   ├── CardFooter.js
│       │   │   ├── CardHeader.js
│       │   │   ├── CardIcon.js
│       │   │   └── CardText.js
│       │   ├── Clearfix
│       │   │   └── Clearfix.js
│       │   ├── CustomButtons
│       │   │   └── Button.js
│       │   ├── CustomDropdown
│       │   │   └── CustomDropdown.js
│       │   ├── CustomInput
│       │   │   └── CustomInput.js
│       │   ├── CustomLinearProgress
│       │   │   └── CustomLinearProgress.js
│       │   ├── CustomTabs
│       │   │   └── CustomTabs.js
│       │   ├── CustomUpload
│       │   │   ├── ImageUpload.js
│       │   │   └── PictureUpload.js
│       │   ├── FixedPlugin
│       │   │   └── FixedPlugin.js
│       │   ├── Footer
│       │   │   └── Footer.js
│       │   ├── Grid
│       │   │   ├── GridContainer.js
│       │   │   └── GridItem.js
│       │   ├── Heading
│       │   │   └── Heading.js
│       │   ├── InfoArea
│       │   │   └── InfoArea.js
│       │   ├── Instruction
│       │   │   └── Instruction.js
│       │   ├── NavPills
│       │   │   └── NavPills.js
│       │   ├── Navbars
│       │   │   ├── AdminNavbar.js
│       │   │   ├── AdminNavbarLinks.js
│       │   │   └── AuthNavbar.js
│       │   ├── Pagination
│       │   │   └── Pagination.js
│       │   ├── ReactTable
│       │   │   └── ReactTable.js
│       │   ├── Sidebar
│       │   │   └── Sidebar.js
│       │   ├── Snackbar
│       │   │   ├── Snackbar.js
│       │   │   └── SnackbarContent.js
│       │   ├── Table
│       │   │   └── Table.js
│       │   ├── Tasks
│       │   │   └── Tasks.js
│       │   ├── Timeline
│       │   │   └── Timeline.js
│       │   ├── Typography
│       │   │   ├── Danger.js
│       │   │   ├── Info.js
│       │   │   ├── Muted.js
│       │   │   ├── Primary.js
│       │   │   ├── Quote.js
│       │   │   ├── Success.js
│       │   │   └── Warning.js
│       │   └── Wizard
│       │       └── Wizard.js
│       ├── index.js
│       ├── layouts
│       │   ├── Admin.js
│       │   ├── Auth.js
│       │   └── RTL.js
│       ├── reducers
│       │   ├── authReducer.js
│       │   └── index.js
│       ├── routes.js
│       ├── services
│       │   └── oauth.js
│       ├── store.js
│       ├── utils
│       │   ├── authProvider.js
│       │   ├── axiosHeaders.js
│       │   └── protectedRoute.js
│       ├── variables
│       │   ├── charts.js
│       │   └── general.js
│       └── views
│           ├── Calendar
│           │   └── Calendar.js
│           ├── Charts
│           │   └── Charts.js
│           ├── Components
│           │   ├── Buttons.js
│           │   ├── GridSystem.js
│           │   ├── Icons.js
│           │   ├── Notifications.js
│           │   ├── Panels.js
│           │   ├── SweetAlert.js
│           │   └── Typography.js
│           ├── Dashboard
│           │   └── Dashboard.js
│           ├── Forms
│           │   ├── ExtendedForms.js
│           │   ├── RegularForms.js
│           │   ├── ValidationForms.js
│           │   ├── Wizard.js
│           │   └── WizardSteps
│           │       ├── Step1.js
│           │       ├── Step2.js
│           │       └── Step3.js
│           ├── Maps
│           │   ├── FullScreenMap.js
│           │   ├── GoogleMaps.js
│           │   └── VectorMap.js
│           ├── Notifications
│           │   └── Notifications.js
│           ├── Pages
│           │   ├── ErrorPage.js
│           │   ├── LockScreenPage.js
│           │   ├── LoginPage.js
│           │   ├── PricingPage.js
│           │   ├── RTLSupport.js
│           │   ├── RegisterPage.js
│           │   ├── Timeline.js
│           │   └── UserProfile.js
│           ├── Post
│           │   ├── Post.js
│           │   └── Posts.js
│           ├── Tables
│           │   ├── ExtendedTables.js
│           │   ├── ReactTables.js
│           │   └── RegularTables.js
│           ├── UserProfile
│           │   ├── RegisterPage.js
│           │   └── UserProfile.js
│           ├── Users
│           │   ├── user.js
│           │   └── users.js
│           └── Widgets
│               └── Widgets.js
└── docker-compose.yml
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">


## Resources
- [Live Preview](https://demos.creative-tim.com/material-dashboard-pro-react-asp-net)
- Buy Page: https://www.creative-tim.com/product/material-dashboard-pro-react-aspnet
- Documentation is [here](https://demos.creative-tim.com/material-dashboard-pro-react-asp-net)
- License Agreement: https://www.creative-tim.com/license
- Support: https://www.creative-tim.com/contact-us
- Issues: [Github Issues Page](https://github.com/creativetimofficial/ct-material-dashboard-pro-react-aspnet/issues)
- Material Dashboard React Asp.net - [demo](https://www.creative-tim.com/product/material-dashboard-react-asp-net?ref=github-md-pro-react-aspnet)
- For Front End Development - [Material Kit Pro React ](https://www.creative-tim.com/product/material-kit-pro-react?ref=github-md-pro-react-aspnet)

## Reporting Issues
We use GitHub Issues as the official bug tracker for the Material Dashboard Pro. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Material Dashboard Pro. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us) instead of opening an issue.

## Licensing

- Copyright 2021 Creative Tim (https://www.creative-tim.com)
- Creative Tim [license](https://www.creative-tim.com/license)

## Useful Links

 - [More products](https://www.creative-tim.com/bootstrap-themes) from Creative Tim

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)

- [Freebies](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim

- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)

##### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>
