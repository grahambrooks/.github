---
name: testing-best-practices
description: Guide for writing effective tests with proper coverage and meaningful assertions.
license: MIT
---

# Testing Best Practices Skill

This skill provides comprehensive guidance for writing and maintaining high-quality tests across all projects in the organization.

## Instructions

Follow these testing best practices:

1. **Test Structure**
   - Use the Arrange-Act-Assert (AAA) pattern
   - Keep tests focused on a single behavior
   - Use descriptive test names that explain what is being tested
   - Organize tests logically (by feature or component)

2. **Test Coverage**
   - Aim for meaningful coverage, not just high percentages
   - Cover happy paths and edge cases
   - Test error conditions and failure scenarios
   - Include integration tests for critical paths

3. **Test Quality**
   - Make tests independent and isolated
   - Avoid test interdependencies
   - Use appropriate mocking and stubbing
   - Keep tests maintainable and easy to understand

4. **Assertions**
   - Use specific, meaningful assertions
   - Avoid testing implementation details
   - Test behavior, not internals
   - Include helpful error messages

5. **Performance**
   - Keep unit tests fast
   - Use appropriate test data sizes
   - Consider parallel test execution
   - Optimize slow tests

6. **Maintenance**
   - Update tests when requirements change
   - Remove obsolete tests
   - Refactor tests to reduce duplication
   - Keep test code as clean as production code

## Usage

This skill will help guide test creation and review across all repositories in the organization.
