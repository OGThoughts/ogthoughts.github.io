function openTab(event, tabId) {
    // Hide all tab content
    const tabContents = document.querySelectorAll('.tab-content');
    tabContents.forEach(content => content.classList.remove('active'));

    // Remove active class from all buttons
    const tabButtons = document.querySelectorAll('.tab-button');
    tabButtons.forEach(button => button.classList.remove('active'));

    // Show the clicked tab content
    document.getElementById(tabId).classList.add('active');

    // Add active class to the clicked button
    event.currentTarget.classList.add('active');
}
