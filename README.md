# Online-Voting-with-C

## Description  
This project is a simple **Online Voting System** implemented in C. It allows users to register candidates, cast votes, and determine the winner based on the majority votes. The system ensures fair voting by validating inputs and preventing duplicate symbols for candidates.  

---

## Features  
✅ Register up to **10 candidates** with unique symbols.  
✅ Allows multiple voters to cast their votes.  
✅ Displays all candidates with their assigned symbols.  
✅ Ensures valid votes by checking user input.  
✅ Declares the winner based on the highest votes.  
✅ Detects a **tie scenario** if multiple candidates receive the highest votes.  

---

## How It Works  
1. **Enter the number of candidates** (maximum 10).  
2. **Assign symbols and names** to candidates.  
3. **Enter the number of voters** participating.  
4. Each voter casts their vote by selecting a candidate.  
5. The system **calculates the results** and displays the winner or a tie if applicable.  

---

## Installation & Execution  

### Prerequisites  
- A **C compiler** (GCC recommended)  
- A terminal or command prompt  

### Steps to Run  
1. **Clone the Repository**  
   ```sh
   git clone [https://github.com/yourusername/Online-Voting-with-C.git](https://github.com/pratik-chau/Online-Voting-with-C.git)  
   cd Online-Voting-with-C  
   ```
2. **Compile the Code**  
   ```sh
   gcc online_voting.c -o voting  
   ```
3. **Run the Program**  
   ```sh
   ./voting  
   ```

---

## Code Structure  

| File | Description |
|------|-------------|
| `online_voting.c` | Contains the main logic for candidate registration, voting, and result computation. |

---
 
📌 **GitHub Repository:** [Online-Voting-with-C](https://github.com/pratik-chau/Online-Voting-with-C)  

Happy Coding! 🚀
