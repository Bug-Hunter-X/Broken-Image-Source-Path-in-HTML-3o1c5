# Broken Image Source Path in HTML

This repository demonstrates a common, yet often overlooked, HTML error: referencing an image with a broken or incorrect source path. This can lead to unexpected behavior in your webpage, disrupting the visual presentation and potentially creating issues for accessibility.

## The Bug

The `bug.html` file contains an `<img>` tag that attempts to load an image from a non-existent or inaccessible path ('broken-image.jpg'). This causes the image to not appear, potentially leading to layout problems and user confusion.

## The Solution

The `bugSolution.html` file provides a solution.  It addresses the issue by using a valid image path, ensuring that the image is correctly loaded and displayed.  Consider adding error handling for more robust solutions in real-world scenarios.