# Regular Expression Projects

This repository contains a set of tasks focused on extracting specific information from structured text using regular expressions. The goal is to practice using regex patterns to extract names, phone numbers, and email addresses from different textual formats.

## Project Overview

There are three tasks in this project:

### Task 1: Basic Extraction

**File structure:**
- The input data is organized in the following format:Name Phone Email

**Objective:**
- Extract:
1. Names
2. Phone numbers (starting with 010, 011, 012, or 015 followed by 8 digits)
3. Email addresses (valid email format)

### Task 2: Mixed Input Format

**File structure:**
- The input data comes in a more varied format:
- Name Phone Email
- Phone Name Email
- Email Name Phone


**Objective:**
- Extract:
1. Names
2. Phone numbers (starting with 010, 011, 012, or 015 followed by 8 digits)
3. Email addresses (valid email format)
### Task 3: Delimited Input Format

**File structure:**
- The input data is delimited by commas or hyphens:
- Name, Phone Number, Email
- Name-Phone Number-Email

**Objective:**
- Handle the delimited format and extract the following:
1. Names
2. Phone numbers
3. Email addresses

---

## Installation and Setup

To run the scripts, ensure that Python is installed on your system. No external libraries are required other than the built-in `re` module in Python for handling regular expressions.

## Usage

1. Place the text files (e.g., `Fake_emails.txt`) in the appropriate directory.
2. Run the scripts for each task, and the results will display the extracted names, phone numbers, and email addresses.

---

