Proposal files:https://drive.google.com/drive/folders/1azyUA2KHoWKLTjlD60tT9K7PnDGTrF6G?usp=sharing
```mermaid
flowchart LR

    Guest[Guest User]
    Customer[Customer]
    Admin[Admin]
    SuperAdmin[Super Admin]

    UC1((Browse Products))
    UC2((Search Products))
    UC3((Register))
    UC4((Login))
    UC5((Manage Cart))
    UC6((Wishlist))
    UC7((Place Order))
    UC8((Track Order))

    UC9((Manage Products))
    UC10((Manage Categories))
    UC11((Manage Inventory))
    UC12((Manage Orders))
    UC13((POS Sales))
    UC14((Generate Reports))
    UC15((Manage Settings))

    UC16((Manage Admins))

    Guest --> UC1
    Guest --> UC2
    Guest --> UC3

    Customer --> UC4
    Customer --> UC5
    Customer --> UC6
    Customer --> UC7
    Customer --> UC8

    Admin --> UC9
    Admin --> UC10
    Admin --> UC11
    Admin --> UC12
    Admin --> UC13
    Admin --> UC14
    Admin --> UC15

    SuperAdmin --> UC16
```
