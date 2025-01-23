# Tailwind CSS: Misspelled or Nonexistent Class Names

This repository demonstrates a common yet often overlooked error in Tailwind CSS projects: using misspelled or nonexistent class names.  This issue can lead to unpredictable styling and debugging challenges.

## The Problem

When a typo is introduced into a Tailwind class name (e.g., `text-grayy-500` instead of `text-gray-500`), the class won't apply correctly. Similarly, if you inadvertently use a class name that doesn't exist in your Tailwind configuration, the style won't be applied, often resulting in unexpected behavior.

## The Solution

* **Careful attention to detail:** Double-check all Tailwind class names for typos.  Utilize your IDE's auto-completion features to minimize errors.
* **Purge unused CSS:** Configure your build process to purge unused CSS classes.  This removes unnecessary CSS from your production build, improving performance and reducing the potential for class name errors to go unnoticed.
* **Use a linter:** Employ a linter that can detect potential class name errors. This provides early warnings and helps maintain code quality.
* **Regular code review:** Thoroughly review your Tailwind CSS usage for errors and ensure all styles are working as expected.

This repository shows a simple example of this issue and its solution using JavaScript and Next.js (or similar frameworks).