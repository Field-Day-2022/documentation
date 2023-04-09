# PWA
## Running locally
PWAs are essentially small web apps that users are able to either use in their browser or install for local use.  This is ideal for the Field Day project, as it allows data to be collected offline to be synced with a database later.  The Field Day PWA meets all of the [install criteria](https://web.dev/install-criteria/) required for a safe installation. 

1. Download the [PWA repository]([https://github.com/Field-Day-2022/field-day-2022-webUI](https://github.com/Field-Day-2022/field-day-2022-pwa)) if you haven't already and check out the branch you want to work on
2. In the Web UI directory, open a terminal
3. If this is your first time, run:
> npm install react-scripts
4. Enter the following command:
> npm start
5. For additional information, please view our [example PWA repository](https://github.com/IanSkelskey/advanced-pwa)

## Developing code
The source code is located in the src directory.  Individual components, forms, and pages can be found and modified within subdirectories.  When you're ready to test your code locally, follow the above directions.  When you're ready to deploy your code, follow this [guide](https://create-react-app.dev/docs/deployment/).

## Resources
[PWA explanation](https://en.wikipedia.org/wiki/Progressive_web_app)

[Example PWA repository](https://github.com/IanSkelskey/advanced-pwa)

[Deployment guide](https://create-react-app.dev/docs/deployment/)

## Individual components
[Button](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/Button.jsx) - Generic clickable button

[ConfirmationModal](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/ConfirmationModal.jsx) - Hardcoded modals for each table type and column name

[Dropdown](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/Dropdown.jsx) - Generic dropdown menu

[FormWrapper](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/FormWrapper.jsx) - HTML div wrapper

[Navbar](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/Navbar.jsx) - Top navigation bar

[Notification](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/Notification.jsx) - Generic notification box

[NumberInput](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/NumberInput.jsx) - Input box for numbers with validation, including settings for integers, no precision below tenths, and upper bounds

[PlusMinusButtons](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/PlusMinusButtons.jsx) - Buttons to wrap around the passed children

[SingleCheckbox](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/SingleCheckbox.jsx) - Checkbox input field

[TextInput](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/TextInput.jsx) - Text input field

[ToeCodeInput](https://github.com/Field-Day-2022/field-day-2022-pwa/blob/main/src/components/ToeCodeInput.jsx) - Input field for clipped toes, which are used for identifying previously tracked animals
