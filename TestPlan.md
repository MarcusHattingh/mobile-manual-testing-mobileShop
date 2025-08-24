# Test Plan — MobileShop App

## 1. Introduction
This document outlines the manual testing approach for the MobileShop e-commerce mobile application.

## 2. Objectives
Verify that core functionalities (login, product browsing, cart, checkout) work as intended across supported devices and OS versions.

## 3. Scope
### In Scope
- Functional testing (login, browse, cart, checkout)
- UI and usability testing
- Compatibility (devices, OS versions)
- Basic accessibility
- Install/Uninstall
- Network and interruption handling

### Out of Scope
- Performance and load testing
- Security penetration testing
- Full automation (planned for later)

## 4. Test Items
- MobileShop Android app (v1.0, build TBD)
- Test accounts: testuser@example.com / password Test@123

## 5. Test Approach
- Prepare test cases in TestCases.xlsx
- Execute tests on multiple devices listed in DeviceMatrix.md
- Log defects with screenshots and recordings in Bugs/
- Track execution status in the test case sheet

## 6. Entry Criteria
- App build installed
- Test data ready
- Devices configured

## 7. Exit Criteria
- All P0 and P1 test cases passed
- No critical defects remain open

## 8. Deliverables
- Test plan
- Test cases
- Bug reports
- Test execution report

## 9. Tools
- GitHub for documentation
- Excel for test cases
- Native screenshot/recording tools

## 10. Risks
- Limited device availability
- Delayed builds from development
