
# NIST 800-53 Control Mapping Matrix

## Purpose
This matrix documents the relationship between
fictional business operational audits, identified
risks, existing procedures, and applicable NIST
SP 800-53 Revision 5 controls.

## Control Mapping Matrix

| Audit ID | Operational Audit | Business Risk | NIST Control | Control Name | Mapping Rationale |
|----------|-------------------|---------------|--------------|--------------|-------------------|
| OA-001 | Financial Transaction Audit | Unauthorized transactions may go undetected | AU-6 | Audit Record Review, Analysis, and Reporting | Transaction logs and exception records can be reviewed to identify suspicious activity. |
| OA-002 | Employee Access Audit | Employees may retain unnecessary system access | AC-2 | Account Management | Account permissions and account status should be reviewed and managed. |
| OA-003 | Employee Access Audit | Employees may have excessive permissions | AC-6 | Least Privilege | User access should be limited to the privileges necessary for assigned duties. |
| OA-004 | Employee Termination Audit | Former employees may retain system access | PS-4 | Personnel Termination | Access and organizational property should be addressed during employee termination. |
| OA-005 | IT Asset Inventory Audit | Unauthorized or unmanaged devices may connect to systems | CM-8 | System Component Inventory | Organizations maintain inventories of system components. |

## Mapping Limitations

These mappings represent potential relationships
between fictional operational audit procedures and
NIST controls.

A mapping does not automatically establish control
implementation or compliance.

Each mapping must be validated against the complete
NIST control language and the organization's actual
environment.
