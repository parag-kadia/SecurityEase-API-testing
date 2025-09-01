# SecuritiEase-API-testing

**API Test Report for https://restcountries.com/v3.1/all/**
This report summarizes the results of three test scenarios conducted on the **restcountries.com** API. The tests were designed to validate data integrity and confirm specific information crucial for various applications.
I have added the screenshot as well from my Postman tests in the SCreenshot folder.

**1. Scheme Validation**

**Purpose:** To ensure the API response adheres to a published data structure.

**Result:** I am unable to perform the schema validation test because the API endpoint https://restcountries.com/v3.1/all/ is currently inaccessible. Given API is updated 2 months ago. To make the API accesible, we must specify **fields** when calling **all** emdpoint

**2. Country Count Confirmation**

**Purpose:** To verify that the API returns a list of 195 countries, aligning with standard geopolitical counts.

**Result:** Fail. The API returned a list of 250 entries, including countries, territories, and other entities. This result does not match the expected count of 195 sovereign states.

**3. South African Sign Language (SASL) Validation**

**Purpose:** To confirm that South African Sign Language is listed as an official language for South Africa in the API data.

**Result:** Fail. The API's data for South Africa lists 11 official languages, none of which is South African Sign Language (SASL).
