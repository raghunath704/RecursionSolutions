# Recursion Solutions from Aditya Verma Recursion Playlist

This repository contains recursion solutions based on **Aditya Verma's Recursion Playlist** on YouTube. All solutions follow the **IBH (Induction-Base-Hypothesis)** method and **Input-Output Method** taught by Aditya Verma.

## About Aditya Verma's Approach

Aditya Verma teaches recursion using two main methods, which makes recursion problems much easier to understand and solve systematically.

## Aditya Verma's Two Methods

### Method 1: IBH Method (Induction-Base-Hypothesis)

#### **I - Induction (The Leap of Faith)**
- Assume your function works correctly for smaller inputs
- Don't try to trace through every recursive call
- Trust that the recursive call will give you the correct result

#### **B - Base Condition** 
- The smallest valid input where you know the answer directly
- The condition that stops the recursion
- Usually the simplest case (like n=0, n=1, empty array, etc.)

#### **H - Hypothesis**
- What does your function do?
- Define clearly what your function returns/calculates
- This helps in making the recursive call correctly

### Method 2: Input-Output Method

#### **Step 1: Identify the Input**
- What are you passing to the function?
- What parameters does your recursive function take?

#### **Step 2: Identify the Output**
- What should the function return?
- What is the expected result/output?

#### **Step 3: Choice and Decision**
- What choices do you have at each step?
- What decisions need to be made in recursion?
- Usually involves include/exclude, take/don't take scenarios

## Templates

### IBH Template
```cpp
returnType solve(parameters) {
    // BASE CONDITION
    if (smallest_valid_input) {
        return direct_answer;
    }
    
    // HYPOTHESIS 
    // Assume solve() works for smaller input
    // Make recursive call with smaller input
    
    // INDUCTION
    // Use the result from hypothesis to solve current problem
    // Combine recursive result with current logic
    
    return final_answer;
}
```

### Input-Output Method Template
```cpp
returnType solve(input_parameters) {
    // INPUT: What am I receiving?
    // OUTPUT: What should I return?
    
    // BASE CONDITION
    if (base_case) {
        return base_result;
    }
    
    // CHOICE & DECISION
    // Option 1: Include/Take current element
    result1 = solve(modified_input_1);
    
    // Option 2: Exclude/Don't take current element  
    result2 = solve(modified_input_2);
    
    // Return based on problem requirement
    return combine(result1, result2);
}
```

## Solutions (Based on Aditya Verma's Playlist Order)

### 1. Introduction to Recursion
- [ ] **Video 1:** Introduction to Recursion
- [ ] **Video 2:** Print 1 to N using Recursion
- [ ] **Video 3:** Print N to 1 using Recursion

### 2. Basic Recursion Problems
- [ ] **Video 4:** Height of Tree
- [ ] **Video 5:** Sort an Array using Recursion
- [ ] **Video 6:** Induction, Base Condition & Hypothesis (IBH Method)

### 3. Stack Problems using Recursion
- [ ] **Video 7:** Delete middle element of Stack
- [ ] **Video 8:** Reverse a Stack using Recursion
- [ ] **Video 9:** Sort a Stack using Recursion

### 4. String Problems
- [ ] **Video 10:** Kth Symbol in Grammar
- [ ] **Video 11:** Josephus Problem
- [ ] **Video 12:** Print all Subsets | Print all Subsequences
- [ ] **Video 13:** Print Unique Subsets
- [ ] **Video 14:** Print all Permutations of String | Array

### 5. Advanced Recursion Problems
- [ ] **Video 15:** Generate all Balanced Parentheses
- [ ] **Video 16:** Print N-bit binary numbers having more 1s than 0s
- [ ] **Video 17:** Tower of Hanoi
- [ ] **Video 18:** Letter Case Permutation

### 6. Recursion Tree Method
- [ ] **Video 19:** Recursion on Tree (Various Tree Problems)
- [ ] **Video 20:** All possible paths from root to leaf

## Aditya Verma's YouTube Channel

**Original Recursion Playlist:** [Aditya Verma - Recursion Playlist](https://www.youtube.com/playlist?list=PL_z_8CaSLPWeT1ffjiImo0sYTcnLzo-wY)

**Playlist Statistics:**
- Total Videos: ~20 videos
- Duration: Complete beginner to advanced level
- Approach: IBH (Induction-Base-Hypothesis) method
- Language: Primarily C++ with clear explanations

## How to Use This Repository

1. **Watch Aditya Verma's video** for the specific problem
2. **Choose your approach**: 
   - Use **IBH Method** for simpler, direct recursion problems
   - Use **Input-Output Method** for choice-based problems (subsets, permutations)
3. **Try to solve it yourself** using the chosen method
4. **Check the solution here** for reference
5. **Practice the approach** on similar problems

### When to Use Which Method?

**IBH Method** is better for:
- Tree problems (height, traversal)
- Mathematical problems (factorial, fibonacci)
- Simple array/string problems

**Input-Output Method** is better for:
- Subset/Subsequence problems
- Permutation/Combination problems  
- Problems with clear include/exclude choices
- Backtracking problems

## Key Takeaways from Aditya Verma

### IBH Method Tips:
1. **Don't trace recursion** - Trust the process (Induction)
2. **Always start with base condition**
3. **Define your hypothesis clearly**
4. **Recursion is just a leap of faith**

### Input-Output Method Tips:
1. **Clearly define Input and Output** before writing code
2. **Identify choices/decisions** at each recursive step
3. **Think in terms of include/exclude** for most problems
4. **Combine results** based on problem requirements

### General Recursion Tips:
5. **Use both methods** - some problems are easier with one approach
6. **Practice the templates consistently**
7. **Start with smaller examples** to understand the pattern

## Credits

All credit goes to **Aditya Verma** for his amazing teaching methodology. This repository is just for practice and reference based on his tutorials.

---

*"Recursion is not about tracing, it's about faith!"* - Aditya Verma
