### 1\. Rolls Table

Purpose: Tracks details of each paper roll.

Columns:

-   ReelNumber
-   GSM
-   Grade
-   Width
-   Length
-   Breaks
-   Comments
-   CurrentLocation
-   Status
-   QRCode

### 2\. Trucks Table

Purpose: Manages information about trucks entering and exiting the premises.

Columns:

-   TruckNumber
-   DriverName
-   TruckStatus
-   TareWeight
-   GrossWeight
-   NetWeight

### 3\. Customers Table

Purpose: Stores details about customers.

Columns:

-   CustomerID
-   CustomerName
-   ContactName
-   ContactEmail
-   ContactPhone
-   Address

### 4\. Suppliers Table

Purpose: Keeps track of suppliers for raw materials.

Columns:

-   SupplierID
-   SupplierName
-   ContactName
-   ContactEmail
-   ContactPhone
-   Address

### 5\. Raw Materials Table

Purpose: Records details about raw materials received.

Columns:

-   MaterialID
-   MaterialName
-   MaterialType
-   SupplierID
-   NetWeight
-   PricePerUnit
-   PurchaseDate
-   TruckNumber
-   Status
-   CurrentLocation
-   PurchaseID

### 6\. Sales Orders Table

Purpose: Manages sales orders.

Columns:

-   OrderID
-   CustomerID
-   TruckNumber
-   Status
-   OrderDate
-   NetWeight

### 7\. OrderDetails Table

Purpose: Links rolls to specific sales orders.

Columns:

-   OrderDetailID
-   OrderID
-   ReelNumber

### 8\. Purchases Table

Purpose: Tracks purchases of supplies.

Columns:

-   PurchaseID
-   SupplierID
-   TruckNumber
-   NetWeight
-   PurchaseDate
-   Status
-   TotalCost
