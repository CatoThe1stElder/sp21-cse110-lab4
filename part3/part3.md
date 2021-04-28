# **Part 3. Debugging using the DevTools**
### **DevTools - Debugging**
1. The bug was the variables `num1` and `num2` are classified as strings, not ints. This simply makes them be *concatenated*, not added.
2. Simply used `parseInt()` to convert `num1` and `num2` to ints before computing. Refer to **img3.png**

### **DevTools - Network Tab**
3. **citylots.json**
   
4. **part2.js**

5. 11687628 bytes

6. 1.19s
7. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.85 Safari/537.36
8. Apache
9. Tue, 26 Jan 2021 22:14:13 GMT
10. application/json
11. `fetchData`