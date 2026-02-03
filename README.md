# Module 1: Python Basics

**Python for Business | FinHub | Rotman School of Management**

---

## Overview

Starting with a simple question — "What's my stock position worth?" — this module introduces Python fundamentals through the lens of finance. You'll build four graphs from real stock data while learning the building blocks of programming.

## The Scenario

You have 100 shares of Apple stock at $150.25 per share. What's your position worth? How much did you make today? This week? Compared to Microsoft?

## What You'll Build

| Graph | What It Answers |
|-------|-----------------|
| Stock Prices | How have these stocks moved over time? |
| Daily Returns | How much did AAPL move each day? |
| Return Distribution | What's a "normal" day look like? |
| Stock Comparison | Which stock performed best? |

## Key Concepts

| Concept | Example | Use Case |
|---------|---------|----------|
| Variables | `price = 150.25` | Store values for reuse |
| Data types | `str`, `int`, `float`, `list` | Different kinds of data |
| Lists | `[100.00, 102.50, 101.25]` | Hold multiple values |
| Loops | `for i in range(n):` | Repeat calculations |
| Functions | `def calculate_return(today, yesterday):` | Reusable code blocks |

## Why Returns Instead of Prices?

A stock at $500 isn't "better" than one at $50. We need **percentage changes** to compare how fast invested wealth grows.

$$\text{return} = \frac{\text{today's price} - \text{yesterday's price}}{\text{yesterday's price}}$$

## Files

| File | Description |
|------|-------------|
| `module1_python_basics.ipynb` | Main notebook with code examples and exercises |

## Exercises

1. **Exercise 1.1:** Write a `win_rate` function that calculates what percentage of returns were positive
2. **Exercise 1.2:** Find AAPL's best and worst single days
3. **Exercise 1.3:** Commit your work to GitHub

---

**Next:** Module 2 — Working with Data (Pandas)
