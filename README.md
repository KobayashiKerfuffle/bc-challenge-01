# bc-challenge-01
01 HTML, CSS, and Git: Code Refactor

# Horiseon Marketing Solutions - Accessibility Update

Horiseon Marketing Solutions offers cutting-edge solutions for digital presence and online marketing. This repository contains the codebase for the Horiseon website, which has been updated to meet accessibility standards.

## Project Overview

The primary goal of this update was to make sure the website adheres to accessibility standards, optimizing it for search engines and ensuring it's user-friendly for all visitors.

## User Story

- AS A marketing agency
- I WANT a codebase that follows accessibility standards
- SO THAT our own site is optimized for search engines

## Acceptance Criteria

- GIVEN a webpage meets accessibility standards
- WHEN I view the source code
- THEN I find semantic HTML elements
- WHEN I view the structure of the HTML elements
- THEN I find that the elements follow a logical structure independent of styling and positioning
- WHEN I view the icon and image elements
- THEN I find accessible alt attributes
- WHEN I view the heading attributes
- THEN they fall in sequential order
- WHEN I view the title element
- THEN I find a concise, descriptive title

## Changes Made

- Semantic HTML Elements: Non-semantic elements like <div> have been replaced with semantic ones such as <header>, <nav>, <section>, <article>, <aside>, and <footer>.
- Logical Structure: Adjustments have been made to ensure that the structure of HTML is logical and consistent, irrespective of the CSS styling.
- Accessible Alt Attributes: All images now contain meaningful alt attributes to ensure screen readers can effectively communicate their purpose.
- Heading Structure: Headings (<h1>, <h2>, etc.) have been organized to follow a sequential and hierarchical structure.
- Descriptive Title: The title has been updated to "Horiseon Marketing Solutions" to more accurately describe the site's content.
- CSS Updates: The CSS has been refactored to clean up redundancies and ensure styles match the updated HTML structure.

## Installation

Clone the repository using the following command: git clone git@github.com:KobayashiKerfuffle/bc-challenge-01.git

## Usage

Navigate through and review the updated HTML and CSS code and assess for accessibility improvements.

## Credits

Original design and assets provided by Horiseon.
Code refactor and accessibility updates by Peter Sadauskas.

## License

This project is licensed under the MIT License.