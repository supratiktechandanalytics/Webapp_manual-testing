**1. Introduction**
This test plan outlines the approach, scope, objectives, and resources for testing the BrowserStack website manually to ensure its quality, usability, and functionality.

**2. Objectives**
Verify the functionality of core features (e.g., sign-up, login, browser/device selection, testing environments, and integration tools).
Ensure the website is responsive and works across different browsers, devices, and screen sizes.
Validate usability, performance, and compatibility aspects.
Identify and report any defects or issues.
**3. Scope of Testing**
Functional Testing: Core features like login, sign-up, dashboard navigation, and live testing.
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>Functional Test Cases</h2>
    <table>
        <thead>
            <tr>
                <th>Test Case ID</th>
                <th>Test Scenario</th>
                <th>Test Steps</th>
                <th>Expected Result</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>TC01</td>
                <td>Verify login with valid credentials</td>
                <td>
                    1. Open the BrowserStack login page.<br>
                    2. Enter valid username and password.<br>
                    3. Click "Login".
                </td>
                <td>User should be redirected to the dashboard.</td>
            </tr>
            <tr>
                <td>TC02</td>
                <td>Verify login with invalid credentials</td>
                <td>
                    1. Open the login page.<br>
                    2. Enter invalid username or password.<br>
                    3. Click "Login".
                </td>
                <td>Error message should appear: "Invalid username or password".</td>
            </tr>
            <tr>
                <td>TC03</td>
                <td>Verify live testing feature</td>
                <td>
                    1. Navigate to the "Live Testing" section.<br>
                    2. Select a browser and operating system.<br>
                    3. Start a session.
                </td>
                <td>Live testing session should start successfully.</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>UI/UX Test Cases</h2>
    <table>
        <thead>
            <tr>
                <th>Test Case ID</th>
                <th>Test Scenario</th>
                <th>Test Steps</th>
                <th>Expected Result</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>TC04</td>
                <td>Verify homepage responsiveness</td>
                <td>
                    1. Open the homepage on desktop, tablet, and mobile devices.
                </td>
                <td>Layout and elements should adjust dynamically to fit screen sizes.</td>
            </tr>
            <tr>
                <td>TC05</td>
                <td>Verify navigation bar functionality</td>
                <td>
                    1. Hover over or click on navigation bar elements.<br>
                    2. Click each menu option to verify navigation.
                </td>
                <td>All menu options should work as expected and navigate to the correct page.</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>Cross-Browser Test Cases</h2>
    <table>
        <thead>
            <tr>
                <th>Test Case ID</th>
                <th>Test Scenario</th>
                <th>Test Steps</th>
                <th>Expected Result</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>TC06</td>
                <td>Verify compatibility on Chrome</td>
                <td>
                    1. Open the website in Chrome.<br>
                    2. Navigate through all core functionalities.
                </td>
                <td>Website should load and function without any errors.</td
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>Bug Report</h2>
    <table>
        <thead>
            <tr>
                <th>Field</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Bug ID</td>
                <td>BUG001</td>
            </tr>
            <tr>
                <td>Module/Feature</td>
                <td>Login Page</td>
            </tr>
            <tr>
                <td>Severity</td>
                <td>High</td>
            </tr>
            <tr>
                <td>Priority</td>
                <td>High</td>
            </tr>
            <tr>
                <td>Summary</td>
                <td>Login button is not functional.</td>
            </tr>
            <tr>
                <td>Steps to Reproduce</td>
                <td>
                    1. Navigate to the login page.<br>
                    2. Enter valid credentials.<br>
                    3. Click the "Login" button.
                </td>
            </tr>
            <tr>
                <td>Expected Result</td>
                <td>User should be logged in and redirected to the dashboard.</td>
            </tr>
            <tr>
                <td>Actual Result</td>
                <td>Login button does not respond to clicks.</td>
            </tr>
            <tr>
                <td>Attachments</td>
                <td>Screenshot attached showing the issue.</td>
            </tr>
            <tr>
                <td>Reported By</td>
                <td>Supratik Sarkar</td>
            </tr>
            <tr>
                <td>Date</td>
                <td>29-Nov-2024</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
