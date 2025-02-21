# Direct Field Access in C#

This repository demonstrates a common C# coding error: directly accessing a private backing field instead of using its corresponding public property.

## The Problem

Directly accessing private fields breaks encapsulation. Changes to the field's behavior (e.g., adding validation or logic to the setter) will not be reflected in code that directly manipulates the field. This can lead to inconsistent behavior, bugs, and difficulty in maintaining the code.

## The Solution

Always use the public property to access and modify the field's value. This ensures that any logic or validation within the property is correctly applied.