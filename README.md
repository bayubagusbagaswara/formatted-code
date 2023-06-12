# Catatan

# ESB-SERVICE-COMMON

Butuh dependency :

- user-management-service
- transaction-history-management-service

# Urutan Build Project

1. parameter-management-service (SUCCESS) branch dev-gcp
2. audit-management-service (SUCCESS) branch dev-gcp
3. authorization-management-service (SUCCESS) branch dev-gcp
4. user-management-service (SUCCESS) branch dev-gcp
5. favorite-management-service (SUCCESS) branch main
6. islamic-management-service (SUCCESS) branch main
7. my-account-management-service (SUCCESS) branch main
8. promo-management-service (SUCCESS), branch dev-gcp
9. user-management-service (SUCCESS) branch dev-gcp
10. notification-management-service (SUCCESS) branch main (NOTED: BUILD ULANG NANTI)

    - user-management-service (SUDAH)
    - promo-management-service (SUDAH)
    - transaction-history-management-service (bisa di comment dulu, termasuk semua coding yg berhubungan, nanti build lagi)
    - esb-service-common 1.0.1-SNAPSHOT (ini di branch development) (bisa di comment dulu, termasuk semua coding yg berhubungan, nanti build lagi)

11. otp-management-service (SUCCESS) branch main

    - notification-management-service (SUDAH)
    - user-management-service (SUDAH)

12. portal-management-service (SUCCESS) branch main (NOTED: BUILD ULANG NANTI)

    - otp-management-service (SUDAH)
    - user-management-service (SUDAH)
    - notification-management-service (SUDAH)
    - limit-management-service (di comment dulu, nanti di build ulang)
    - promo-management-service (SUDAH)

13. transaction-history-management-service (SUCCESS) branch main

    - notification-management-service (SUDAH)
    - portal-management-service (SUDAH)

14. limit-management-service (SUCCESS) branch main

    - transaction-history-management-service (SUDAH)

15. scheduler-management-service (ERROR)

    - notification-management-service

16. scheduler-transaction-management-service (ERROR),

    - ist-api-parent version 1.1.0
