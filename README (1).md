# Crown & Blade -- Salon Queue Management System

A simple, browser-based queue management system for a salon. **Crown &
Blade** helps customers join the service queue and allows salon staff to
manage appointments, walk-ins, barber availability, and live queue
progress from dedicated screens.

## Live Demo

[Open Crown & Blade -- Live Queue
System](https://magenta-gecko-78a683.netlify.app/)

## Project Overview

The application is designed to make salon queue handling more organised
and transparent. Customers can enter the queue by selecting the services
they need, while reception staff and barbers can update each token as
the service progresses. A separate TV display can show the current and
upcoming customers.

The interface also includes Gujarati language support.

## Main Features

### Customer Queue

-   Join the queue by entering customer details.
-   Select the required salon services (up to three services).
-   Choose a preferred barber, where applicable.
-   Receive a queue token and view queue status.
-   View an estimated waiting time.
-   Cancel a queue token.

### Reception Dashboard

-   View and manage the customer queue.
-   Call the next eligible customer.
-   Add walk-in customers.
-   Cancel a token.
-   Mark a customer as a no-show.
-   Re-add a no-show customer to the queue when required.

### Barber Dashboard

-   View customers assigned or available for service.
-   Start and complete a service.
-   Update barber availability by switching break status.

### TV Display

-   Display the customer currently being served.
-   Display the next customers in the queue.
-   Enable or disable the queue announcement chime.

### Owner / Settings

-   Enable or disable online queue entry.
-   Manage barber duty status.
-   Enable or disable services.
-   View queue-related statistics.

### Additional Interface Features

-   English and Gujarati language options.
-   Responsive interface for different screen sizes.
-   Queue information and estimated wait updates within the application.

## Technology Used

-   **HTML** -- page structure
-   **CSS** -- layout, styling, and responsive design
-   **JavaScript** -- queue operations, dashboard interactions, and
    application logic
-   **Browser local storage** -- persistence of application data in the
    browser

## Run Locally

This is a front-end web application. No package installation is required
for the basic local run.

1.  Clone this repository:

    ``` bash
    git clone <your-repository-url>
    ```

2.  Open the project folder.

3.  Open the main HTML file in a modern web browser.

    Alternatively, use the **Live Server** extension in Visual Studio
    Code to run it locally.

> If you are using the deployed Netlify version, open the Live Demo link
> above.

## How to Use

1.  Open the application.
2.  Use the customer queue screen to enter customer details and select
    services.
3.  Use the reception dashboard to call customers and manage walk-ins.
4.  Use the barber dashboard to start and complete services or update
    break status.
5.  Open the TV display to show the current and upcoming queue.
6.  Use the owner/settings screen to manage online queue access,
    barbers, and services.

## Important Notes

-   The waiting time shown by the application is an **estimate**, not a
    guaranteed service start time. Actual waiting time can change
    depending on service duration, barber availability, and queue
    activity.
-   Browser-based storage is local to the browser/device. This project
    should not be treated as a production, multi-device salon management
    backend unless a shared server/database is added and configured.
-   Avoid entering real customer personal information in a demonstration
    or public deployment.

## Future Enhancements

-   Add a central database and backend API for synchronised multi-device
    operation.
-   Add secure staff and owner authentication.
-   Add SMS or WhatsApp notifications when a customer's turn is
    approaching.
-   Add appointment booking and customer history.
-   Add reports for service volume, barber performance, and daily
    revenue.

## Project Status

A front-end prototype / demonstration of a salon queue management
workflow.

## License

No license has been specified yet. Add a license file if you intend to
make this project open source.
