# Inventory Check Workflow

This workflow verifies item availability in inventory.

## Workflow Details

- **Input Schema**:
  - `item_id`: Unique identifier for the item
  - `quantity`: Requested quantity

- **Main Steps**:
  1. Availability Check
     - Verify item existence
     - Check quantity availability
  2. Response Generation
     - Return boolean availability status

## Usage

Essential for inventory management systems requiring quick availability checks.
