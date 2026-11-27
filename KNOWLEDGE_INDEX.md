# SOLIDWORKS VBA ENGINEERING
# KNOWLEDGE INDEX

## 1. PURPOSE

This repository is the central knowledge base for SolidWorks VBA automation across multiple SolidWorks versions.

All AI assistants working on this project should follow PROJECT_INSTRUCTIONS.md.

## 2. DOCUMENTATION STRUCTURE

### 01_API_DOCUMENTATION
Official SolidWorks API references, interface documentation, methods and properties.

### 02_TYPE_LIBRARIES
Type Library information, COM interfaces, enums, constants and API signatures.

### 03_VERSION_COMPATIBILITY
API availability and compatibility across SolidWorks versions.

### 04_VBA_CODE_LIBRARY
Reusable VBA modules, classes, functions and working macros.

### 05_DEBUG_AND_ERRORS
Compile errors, runtime errors, COM errors and verified solutions.

### 06_PROJECT_HISTORY
Technical decisions, development notes and change history.

## 3. API VERIFICATION RULES

Before using an API:

- Verify the API name.
- Verify the interface.
- Verify method parameters.
- Verify return types.
- Verify enum and constant values.
- Verify version compatibility.

Never invent API signatures.

## 4. VBA CODE QUALITY

All code should:

- Use Option Explicit.
- Declare variables clearly.
- Handle errors safely.
- Check object references.
- Preserve existing functionality.
- Avoid unnecessary COM calls.
- Support the intended SolidWorks versions.

## 5. VERSION COMPATIBILITY

Always identify the target SolidWorks version.

Do not assume APIs are identical across versions.

Document any version-specific differences.

## 6. EVIDENCE CLASSIFICATION

Use these labels:

- VERIFIED: Tested successfully.
- DOCUMENTED: Supported by official documentation.
- UNTESTED: Not tested in SolidWorks.
- UNKNOWN: Insufficient information.

## 7. DEVELOPMENT PRINCIPLE

Prioritize correctness, stability, compatibility, data safety and maintainability.

Do not claim that code has been tested unless actual testing has been performed.
