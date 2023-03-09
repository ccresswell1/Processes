# Claim to Supplier Guide

Process for creating a warranty claim to a supplier. 
<br>
Ensure all items you intend to claim are in bin location 'Z-CLAIMS'

<br>

## 1. MMS130

<br>

- enter item number
- enter warehouse 
- enter bin location -> 'Z-CLAIMS'
- change calc method to 01
- next
- status balance ID -> 3 - rejected
- next 
- close

<br>

## 2. PPS390

<br>

- enter '921' in facility (if not auto-filled)
- 'RTS order type' -> F4 -> L03
- enter facility and warehouse (if not auto-filled)
- enter supplier
- enter PO (if applicable)
- **click '+' sign at top of screen**
- enter WRF number (for Rheem) or M3 order number in 'note' field
- check credit to issue checkbox
- next
- check 'change address' checkbox for both 'supplier address' and 'final destination' 
- next
- select correct addresses for both (Brampton for Rheem)
- next x2 (brings you to PPS391/B)
---
- enter item -> add
- enter returned quantity
- enter reject reason (Q4 for warranty)
- enter expected credit amount in 'price' (or WRF number for Rheem)
- next -> OK (when prompted with warning about 'no receiving number')
---
- repeat previous 5 steps for any additional items (starting from 'enter item')
- close (F3)
- **make note of RTS number**
- Action -> F14 (to print)
- enter RTS number in 'to' and 'from' fields
- next
- confirm output
- OK (on popup)
- close (F3)
- 'browse orders' (top left corner)
- **make note of RO number**
- open MWS300

<br>

## 3. MWS300

<br>

- enter delivery number (from newly printed picking list)
- higlight picking list row
- open picking list lines
- actions -> confirm all

## 4. Await credit

Process credit once it has been issued by the supplier*
