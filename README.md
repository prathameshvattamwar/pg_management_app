
## Local Setup & Usage

1.  **Clone the repository (or download the code):**
    ```bash
    git clone <https://github.com/prathameshvattamwar/pg_management_system>
    cd PG-MANAGEMENT
    ```
2.  **Open `index.html`:** Open the `index.html` file directly in your web browser.

3.  **Login Credentials:**
    *   **Admin:**
        *   Username: `admin`
        *   Password: `password`
        *   Role: Admin
    *   **Tenant:** Credentials are created by the Admin when adding a tenant.
        *   Username: Tenant's 10-digit contact number
        *   Password: `TenantFirstName@RoomNumber` (e.g., `User@1`)
        *   Role: Tenant

## Deployment

This project's frontend is deployed using Vercel. The live link is intended to be accessed via a separate public page/repository.

## Limitations & Notes

*   **LocalStorage Persistence:** All data is stored in the browser's LocalStorage. This means data is specific to that browser and computer, and clearing browser data will erase everything. This is suitable for demonstration or single-user scenarios only.
*   **No Backend/Database:** There is no server-side logic or database. All operations happen client-side.
*   **Security:** Authentication is basic and passwords are shown/generated simply. Not suitable for sensitive data or production use.
*   **Scalability:** Designed for a small scale; performance might degrade with a very large number of rooms/tenants due to reliance on client-side filtering and LocalStorage.
