# Expedia_project [https://www.expedia.com/]

### Test Plan for Expedia Website

**Project Name:** Expedia Website  
**Test Plan Version:** 1.0  
**Prepared By:** [Abhishek Maurya]  
**Date:** [13-11-2024]

#### 1. Introduction
The purpose of this test plan is to verify the functionality, usability, and performance of the Expedia website, focusing on its core features such as search functionality, booking options, and user interactions. The goal is to ensure that the website meets the specified requirements and provides a smooth experience for users.

#### 2. Objectives
- Validate the functionality of the search bar for stays, flights, cars, packages, things to do, and cruises.
- Verify the accuracy and performance of the booking process for various travel services.
- Test the usability and accessibility of the website across different devices and browsers.
- Ensure that error handling and user feedback are appropriate and informative.

#### 3. Scope of Testing
- Functional Testing
- Usability Testing
- Performance Testing
- Compatibility Testing
- Security Testing

#### 4. Test Strategy
1. **Functional Testing**:
   - Verify that the search bar allows users to search for stays, flights, and cars accurately.
   - Check if adding flight/car options updates search parameters correctly.
   - Validate the booking flow for different services.
2. **Usability Testing**:
   - Ensure that the website is easy to navigate.
   - Verify that all buttons, icons, and interactive elements respond correctly.
3. **Performance Testing**:
   - Test loading time of the main page and search results.
   - Monitor website performance with multiple users.
4. **Compatibility Testing**:
   - Test on major browsers (Chrome, Firefox, Edge, Safari).
   - Test on mobile and desktop versions.
5. **Security Testing**:
   - Verify that sensitive information is encrypted.
   - Test for vulnerabilities in login and payment areas.

#### 5. Test Environment
- Browsers: Chrome (latest), Firefox, Safari, Edge
- Devices: Desktop, Mobile (iOS and Android)
- Network: Wi-Fi, 4G/5G

#### 6. Test Cases (Examples)

1. **Search Functionality**  
   - **Test Case ID:** TC001  
   - **Description:** Validate that the search bar can search for locations correctly.  
   - **Steps:**  
     1. Enter a location in the "Where to?" field.
     2. Set dates and travelers.
     3. Click on the "Search" button.
   - **Expected Result:** Search results for the entered location are displayed.

2. **Booking Process**  
   - **Test Case ID:** TC002  
   - **Description:** Ensure that users can book a hotel.  
   - **Steps:**  
     1. Select a hotel from search results.
     2. Follow prompts to complete booking.
     3. Confirm booking details.
   - **Expected Result:** Booking is completed successfully, and confirmation is displayed.

3. **User Interface Validation**  
   - **Test Case ID:** TC003  
   - **Description:** Verify that the "Add a flight" and "Add a car" options update the search fields.  
   - **Steps:**  
     1. Check the "Add a flight" checkbox.
     2. Check the "Add a car" checkbox.
     3. Verify that additional fields appear.
   - **Expected Result:** Additional fields for flight and car options appear.

#### 7. Entry and Exit Criteria

**Entry Criteria**  
- All necessary environments are set up.
- Test data is prepared.
- The Expedia website is accessible.

**Exit Criteria**  
- All high-priority test cases are executed.
- Critical bugs are resolved.
- Test summary report is created.

#### 8. Deliverables
- Test Cases
- Test Results
- Bug Reports
- Test Summary Report

