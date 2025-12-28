# TezBiryani
biryani suggestions
# Biryani Recipe Repo 🍛

Welcome to the **Biryani Recipe Repo**! This repository is a collaborative place for sharing delicious biryani recipes. Contributors can add their own versions of biryani, and the author reviews and merges the ones that fit best.  

---

## 📖 How This Works (Git Analogy)

1. **Main Branch (`main`)**  
   - This is the **official cookbook**.  
   - Only the **author/maintainer** merges recipes here.  

2. **Feature Branches (`feature/*`)**  
   - Contributors create their own branches to **add recipes**.  
   - Example:  
     ```text
     feature/chicken-biryani
     feature/veg-biryani
     feature/hyderabadi-style
     ```

3. **Commits**  
   - Every step in a recipe is a **commit**.  
   - Example: “Add marination instructions” or “Add rice cooking steps”

4. **Pull Request (PR)**  
   - Contributors submit a PR to the author:  
     > “Hey, I added a Chicken Biryani recipe. Can you merge it?”  
   - The author **reviews** the recipe before merging.

5. **Merging**  
   - Only **selected recipes** get merged into `main`.  
   - Now the official cookbook has all the approved recipes.

6. **Conflict Resolution**  
   - If two recipes change the same step differently, the author decides the **final version**.

---

## 🍴 Adding Your Recipe

1. Create a **new branch**:
   ```bash
   git checkout -b feature/my-biryani
