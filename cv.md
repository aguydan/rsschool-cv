# Daniil Pivovarov

##### Frontend Developer

***

### Contact:

**Phone:** +7 9150767326
**Email:** danielpivovarov1@gmail.com
[**LinkedIn**](www.linkedin.com/in/daniel-pivovarov)
[**GitHub**](https://github.com/aguydan)

***

### About Me:

***

### Skills:

- JavaScript, HTML, CSS
- React, Node.js
- Git, GitHub
- VS Code
- Basic understanding of Python

***

### Code Example:

**Remove Duplicates from Sorted Array (LeetCode):** Given an integer array nums sorted in non-decreasing order, remove the duplicates in-place such that each unique element appears only once. The relative order of the elements should be kept the same.

```
function removeDuplicates(nums) {
    let l = 1;
    
    for (let r = 1; r < nums.length; r++) {
        if (nums[r] !== nums[r-1]) {
            nums[l] = nums[r];
            l++;
        }
    }
    
    return l;
}
```

***

### Education:

**RS School** «JavaScript/Front-end» Course
2022 - present

### Languages:

- English: B1/B2 (Intermediate/Upper-Intermediate)
- Russian: C2 (Native)