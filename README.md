ShopGuard — End-to-End QA Framework for E-Commerce Platforms

A structured manual testing suite for a Flutter-based e-commerce mobile application, covering critical user flows from authentication to payment validation.


 Project Overview
ShopGuard is a comprehensive QA project designed to validate the core functionality of a Flutter e-commerce app. The goal was to ensure a bug-free and reliable user experience across all critical modules before production release.
Role: QA Tester
Testing Type: Manual
Platform: Mobile (Flutter/Android)
Duration: December 2025

 Scope of Testing
ModuleTest CasesStatusAuthentication5, CompletedProduct Search4, CompletedCart Management5, CompletedPayment & Checkout5, CompletedTotal2095% Pass Rate

 Testing Techniques Used

Functional Testing — Verified all features work as per requirements
Negative Testing — Invalid inputs, wrong credentials, expired cards
Boundary Value Analysis — Empty fields, max quantity, zero values
Smoke Testing — Critical path validation on each new build
Exploratory Testing — Unscripted testing to discover edge cases


 Bugs Found
Bug IDModuleTitleSeverityBUG001Product SearchApp crashes on special character input CriticalBUG002CartOut-of-stock item can be added to cart, MajorBUG003CartCart badge resets after app restar,t MinorBUG004Product SearchFilter resets when navigating back Minor

 
 Test Execution Summary
Total Test Cases  : 20
Passed            : 18
Failed            : 2
Pass Rate         : 95%
Bugs Reported     : 4 (2 Critical/Major, 2 Minor)

 Tools Used
ToolPurpose
JIRABug tracking and sprint managementGoogle Sheets / ExcelTest case documentationAndroid EmulatorApp testing environmentGit / GitHubVersion control and portfolio

Key Takeaways

Identified a critical crash bug in the search module that would have directly impacted user retention
Found a cart vulnerability allowing out-of-stock items to be purchased
Achieved 95%+ test coverage across all critical user flows
Collaborated with developers to reproduce and verify all reported bugs

