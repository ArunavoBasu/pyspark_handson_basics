# PySpark Basics - Hands-on Guide

This repository contains a **basic PySpark hands-on file** designed to help beginners and practitioners understand the fundamentals of working with PySpark. It covers essential operations for data manipulation, transformation, and writing techniques in distributed environments.

---

## 📘 Overview

PySpark is the Python API for Apache Spark, enabling scalable data processing and analytics.  
This file demonstrates **core operations** such as:

- Creating and manipulating DataFrames  
- Performing joins and handling duplicate columns  
- Applying transformations and actions  
- Writing data with different save modes  

> ⚠️ **Note**: The original file was too large to store directly in the repository, so it has been compressed into a **ZIP file**. Please unzip it before running.

---

## 🔑 Key Concepts Covered

### 1. DataFrame Creation
- How to initialize DataFrames from structured data.
- Understanding schema inference and manual schema definition.

### 2. Joins
- Performing inner joins on common keys.
- Why duplicate columns appear after joins and how to handle them (select, rename, drop).

### 3. Write Modes
PySpark supports four main write modes when saving data:

- **append** → Adds new data to existing dataset.  
- **ignore** → Skips writing if target already exists.  
- **error (errorifexists)** → Throws error if target exists.  
- **overwrite** → Replaces existing dataset with new data.  

### 4. Basic Transformations
- Selecting, filtering, and aggregating data.
- Using `withColumn` and `selectExpr` for column operations.

---
