# Command Line Execution Options

All tests are run using `npx playwright test`. By default, tests run on Chromium, Firefox, and WebKit simultaneously in **headless** mode (no UI).

| **Command**                         | **Purpose**                                                 |
| ----------------------------------- | ----------------------------------------------------------- |
| **Run All Tests**                   | `npx playwright test`                                       |
| **Run Specific File**               | `npx playwright test [FileName].spec.js`                    |
| **Run on Specific Browser**         | `npx playwright test [FileName].spec.js --project=chromium` |
| **Run in Headed Mode (Visible UI)** | `npx playwright test [FileName].spec.js --headed`           |
| **Run in Debug Mode**               | `npx playwright test [FileName].spec.js --debug`            |
| **Show Report**                     | `npx playwright show report`                                |
