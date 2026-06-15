# Football Ticket Booking System

A database design and SQL query assignment for a simplified Football Ticket Booking System. This project demonstrates relational database design, ERD modeling, and intermediate-to-advanced SQL queries.

## Database Schema

### Tables

- **Users** - Stores registered users (Ticket Managers and Football Fans) with fields for name, email, role, and phone number.
- **Matches** - Catalogs tournament matches with fixture details, tournament category, base ticket price, and match status.
- **Bookings** - Transactional records linking users to matches with seat allocation, payment status, and total cost.

### Entity Relationships

- **One to Many** - One User can have many Bookings
- **Many to One** - Many Bookings can belong to one Match
- **One to One (logical)** - Each Booking maps exactly one User to one Match for a specific seat

## Queries Covered

1. Filter matches by tournament category and status
2. Pattern matching with LIKE/ILIKE
3. NULL handling with COALESCE
4. INNER JOIN across three tables
5. LEFT JOIN to include users with no bookings
6. Subquery with aggregate comparison
7. Pagination with LIMIT and OFFSET

## Submission Links

- **ERD:** https://drive.google.com/file/d/1NVKYjqKQtCBuDBVVGOicaMf0WGa5hpRn/view
- **GitHub:** https://github.com/uniqweber/b7-assignment-03.git
- **Interview Video:** https://drive.google.com/drive/folders/1P6utVWwuL3iAfi5pj8pnwiUoZe3VQSjh?usp=sharing
