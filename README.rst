========================================
Unit Testing and Fuzz Testing for CUGR
========================================

Introduction
============

This project aims to add unit testing and fuzz testing to the CUGR (CUHK VLSI Global Router) project, a detailed routability-driven global router developed by the research team supervised by Prof. Evangeline F. Y. Young at The Chinese University of Hong Kong (CUHK). CUGR focuses on the final detailed routing results, adopting several efficient and effective methods for generating connected rectangles that guide the detailed router.

CUGR Github repository: https://github.com/cuhk-eda/cu-gr

Objective
=========

The objective is to develop a comprehensive suite of unit tests and fuzz tests to ensure the correctness, stability, and robustness of the CUGR project. These tests will help identify potential issues and vulnerabilities in the codebase and ensure that the global router performs as expected.

Approach
========

1. Analyze the CUGR project codebase to identify key components and functions that require testing.
2. Develop unit tests for the identified components and functions using appropriate testing frameworks and libraries.
3. Implement fuzz testing to identify vulnerabilities and unexpected behavior in the CUGR project. Fuzz testing involves providing invalid, unexpected, or random data as input to the software to find potential crashes, memory leaks, or other issues.
4. Integrate the unit tests and fuzz tests into the CUGR project's build process, ensuring that all tests are executed and passed during the build.

Technologies
============

The following technologies and libraries will be used for implementing unit tests and fuzz tests for the CUGR project:

1. Google Test: A widely-used C++ testing framework for writing and executing unit tests.
2. LibFuzzer: A library for coverage-guided fuzz testing, which can be used with LLVM's Clang compiler.
3. AddressSanitizer: A fast memory error detector that can be used in conjunction with LibFuzzer to identify memory-related issues.

Plan
====

1. Familiarize yourself with the CUGR project codebase and identify key components and functions that require testing.
2. Set up the testing environment, including installing and configuring Google Test, LibFuzzer, and AddressSanitizer.
3. Write and execute unit tests for the identified components and functions using Google Test.
4. Implement fuzz testing using LibFuzzer and AddressSanitizer to identify vulnerabilities and unexpected behavior in the CUGR project.
5. Integrate the unit tests and fuzz tests into the CUGR project's build process.
6. Document the tests, including the test cases, the testing process, and any issues discovered and resolved during testing.

Group 12
========

- 311551118 | 倪子傑 | `BillyNI-OUO <https://github.com/BillyNI-OUO>`_
- 311551145 | 石孟祐 | `yoyojs200602 <https://github.com/yoyojs200602>`_
- 311551129 | 耿鈺展 | `ksh2027 <https://github.com/ksh2027>`_
- 311553048 | 李承翰 | `darrenleeleelee1 <https://github.com/darrenleeleelee1>`_

