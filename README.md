# git-cafe-exercise

## **Bundle 5**

### **Exercise 1: Enable GitHub Pages**

1. **Navigate to Settings**:

   - Open your GitHub repository.
   - Click on **Settings** in the top menu.

2. **Enable GitHub Pages**:

   - Scroll to the **Pages** section.
   - Under the **Source** dropdown, select a branch (e.g., `main`) and the root folder.
   - Click **Save**.

3. **Check the Public Link**:
   - GitHub will provide a URL like `https://yourusername.github.io/repo-name/`.
   - Open the link in a browser to ensure it’s visible to everyone.

---

### **Exercise 2: Fork and Contribute to `git-cafe-exercise`**

1. **Fork the Repository**:

   - Go to [git-cafe-exercise](https://github.com/TheGymRwanda/git-cafe-exercise).
   - Click **Fork** at the top-right corner to copy it to your account.

2. **Clone the Fork**:

   ```bash
   git clone https://github.com/yourusername/git-cafe-exercise.git
   cd git-cafe-exercise
   ```

3. **Modify `index.html`**:

   - Open the file `index.html` in your editor.
   - Change `Welcome to our place` to `Welcome to our restaurant`.

4. **Commit and Push Changes**:

   ```bash
   git add index.html
   git commit -m "message"
   git push origin main
   ```

5. **Raise a Pull Request (PR)**:
   - Go to your forked repository on GitHub.
   - Click **Contribute** → **Open pull request**.
   - Describe the changes and submit the PR.

---

## **Bundle 6**

> Each exercise involves working on the forked copy of `git-cafe-exercise` from Bundle 5.

### **Exercise 1: Add a Menu Page**

1. **Create a Feature Branch**:

   ```bash
   git checkout -b new-feature
   ```

2. **Add a New Page**:

   - Create a file named `menu.html`.

3. **Commit and Push**:

   ```bash
   git add menu.html
   git commit -m "Added menu page"
   git push
   ```

4. **Raise a PR**:
   - Open a PR from `new-feature` to `main` on GitHub.
   - Request a review.

---

### **Exercise 2: Bug Fix on `index-4.html`**

1. **Create a Bug Fix Branch**:

   ```bash
   git checkout -b bug-fix
   ```

2. **Fix the Title**:

   - Open `index-4.html`.
   - Change the title to `Contact`.

3. **Commit and Push**:

   ```bash
   git add index-4.html
   git commit -m "Fixed title in index-4.html"
   git push
   ```

4. **Raise a PR**:
   - Open a PR from `bug-fix` to `main`.
   - Request a review.

---

### **Exercise 3: Hotfix on Phone Number**

1. **Update the Phone Number**:

   - Edit `index-4.html`.
   - Change `+1 800 603 6035` to `+1 800 659 6035`.

2. **Commit and Push**:

   ```bash
   git add index-4.html
   git commit -m "Updated contact phone number"
   git push
   ```

3. **Raise a PR**:
   - Open a PR from `bug-fix` to `main`.
   - Request a review.

---

### **Exercise 4: Review and Merge PRs**

1. **Access Peers’ Repositories**:

   - Ensure your peers grant you collaborator access to their repositories.

2. **Review PRs**:

   - Open their PRs.
   - Review the code and request changes if needed (e.g., add comments or improve formatting).

3. **Approve and Merge**:
   - After the requested changes are made, approve the PR and merge it.
