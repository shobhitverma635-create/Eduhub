<script>
  // Function to show/hide sections
  function showSection(sectionId) {
    // Hide all sections
    document.querySelectorAll("section").forEach(sec => {
      sec.classList.add("hidden");
    });

    // Show selected section
    document.getElementById(sectionId).classList.remove("hidden");
  }

  // Example for adding new courses (temporary)
  function addNewCourse() {
    alert("Feature coming soon: Add a new course!");
  }

  // Example for logout
  function logout() {
    alert("You have been logged out!");
  }
</script>
