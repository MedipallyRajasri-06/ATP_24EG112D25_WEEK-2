# Week 2 Assignments 
##  Project Structure

| Directory | Description |
| :--- | :--- |
| `Product_Resource` | A RESTful API built with Express for product management. |
| `day3Assignments` | Functional programming exercises using Map, Filter, and Reduce. |
| `day4Assignments` | Advanced object manipulation, deep/shallow copying, and custom array logic. |
| `modularQues` | Practice with ES Modules (import/export) and task validation. |

---

## Detailed Breakdown

### 1. Product Resource API (`Product_Resource`)
A complete backend service for managing a product inventory.

- **Features**:
  - `POST /product`: Create a new product.
  - `GET /product`: Retrieve all products.
  - `GET /product/:brand`: Filter products by brand name.
  - `PUT /product`: Update existing product details.
  - `DELETE /product/:productId`: Remove a product by its unique ID.
- **Tech Stack**: Node.js, Express.js (v5+), ES Modules.
- **Running the Server**:
  ```bash
  cd Product_Resource
  node server.js
  ```

### 2. Day 3: Functional Programming (`day3Assignments`)
- **Key Exercises**:
  - `bankTransaction.js`: Statement summary using `filter`, `map`, and `reduce`.
  - `empPayroll.js`: Employee payroll calculations.
  - `examMarks.js`: Processing student grades.
  - `movieStream.js`: Filtering and mapping movie data.
  - `onlineCourse.js`: Course enrollment logic.
  - `stuPerformance.js`: Detailed performance metrics.
  - `temperature.js`: Data conversion and analysis.

### 3. Day 4: Advanced Logic & Objects (`day4Assignments`)
- **Key Exercises**:
  - `shallowCopy.js` & `deepCopy.js`: Exploring `structuredClone` and object isolation.
  - `extendArray.js`: Adding custom methods to the Array prototype.
  - `librarymanagement.js`: Complex object relationships for book tracking.
  - `updateUserObj.js`: Dynamic object property updates.
  - `OTPCount.js`: State management and logic.

### 4. Modular Task Management (`modularQues`)
- **Architecture**:
  - `validator.js`: Reusable validation logic for task inputs.
  - `task.js`: Core logic for adding and retrieving tasks.
  - `app.js`: Entry point demonstrating the interaction between modules.

