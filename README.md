# Rocillo_Laboratory-Activity-4

# JOIN QUERIES
INNER JOIN
Referrals query → shows only matches between referrers and referred users.

LEFT JOIN
Users + profiles → shows all users, adds profile info if it exists.

RIGHT JOIN
Users + roles → shows all roles, adds user info if it exists.

FULL JOIN
Users + profiles (LEFT + RIGHT with UNION) → shows all users and profiles, even if they don’t match.

CROSS JOIN
Users × roles → shows every user with every role.

SELF JOIN
Referrals query → users table joined to itself to show who referred whom.

LEFT JOIN with Subquery
Users + latest login → shows all users, adds their most recent login if available.

# END POINTS
/api/reports/users-with-roles → retrieves users and their roles.

/api/reports/users-with-profiles → retrieves all users and their profile info (or NULL where no profile info exists).

/api/reports/roles-right-join → retrieves all roles, including user information if it exists; roles without users still appear.

/api/reports/profiles-full-outer → retrieves all users and all profiles, even if they don’t match (emulated with LEFT JOIN + RIGHT JOIN).

/api/reports/user-role-combos → retrieves all users and roles in every possible scenario (CROSS JOIN).

/api/reports/referrals → retrieves details of the referrer and the referred user, showing who invited whom and when (SELF JOIN).

/api/reports/latest-login → retrieves all users and their last login details or NULL if they haven’t logged in yet.
