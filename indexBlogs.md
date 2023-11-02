---
layout: blogs
permalink: /blogs
title: Blogs
---

<!-- Add this button to your user data page -->
<button id="clearDatabaseButton" onclick="clearDatabase()">Clear Database</button>

<script>
function clearDatabase() {
    // Clear the user data database in local storage
    localStorage.removeItem('userDataTable');
    // Reload the page or perform any other action as needed
    location.reload(); // Reload the page to reflect the cleared database
}
</script>

</body>
</html>