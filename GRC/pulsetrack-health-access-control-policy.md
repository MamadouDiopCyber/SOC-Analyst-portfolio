# PulseTrack Health Access Control Policy

## Project Overview

This is a fictional junior GRC portfolio project created to practise writing an access control policy for a healthcare technology company.

The policy helps PulseTrack Health manage access to systems that may store or process electronic protected health information (ePHI).

## Document Information

- Document ID: POL-SEC-001
- Version: 1.0
- Status: Portfolio Practice Draft
- Scenario Organization: PulseTrack Health
- Policy Owner: Information Security
- Review Cycle: Annually

## Purpose

The purpose of this policy is to establish requirements for granting, reviewing, changing, and removing access to PulseTrack Health systems.

This policy supports least privilege, proper authorization, individual accountability, and timely removal of access.

## Scope

This policy applies to employees, contractors, temporary workers, and approved vendors who access:

- Company networks
- AWS cloud resources
- Production databases
- GitHub repositories
- Google Workspace
- Slack
- Applications containing ePHI

## Roles and Responsibilities

### Human Resources

Human Resources must notify IT when an employee or contractor is hired, changes roles, or leaves the organization.

### Managers

Managers must approve access requests and confirm that the requested access is necessary for the user’s job responsibilities.

### IT Administrators

IT administrators must create, change, disable, and remove user accounts based on approved requests.

### Information Security

Information Security must review access controls, document identified gaps, and track corrective actions.

### Users

Users must protect their credentials, follow authentication requirements, and report suspected unauthorized access.

## Access Control Requirements

### Least Privilege

Users must receive only the access necessary to perform their assigned job responsibilities.

Administrative or privileged access must be limited to authorized personnel and approved by management.

### Unique Accounts

Each user must receive an individual account.

Shared accounts must not be used unless there is a documented business need, management approval, and additional monitoring.

### Multifactor Authentication

Multifactor authentication must be enabled for systems containing sensitive information, including:

- AWS
- Google Workspace
- GitHub
- Production systems
- Remote-access services

### Access Requests

New access requests must:

- Be submitted through an approved request or ticketing process
- Identify the system and requested access level
- Include a business justification
- Receive approval from the user’s manager
- Be completed by authorized IT personnel

### Role Changes

When an employee changes roles, the manager and IT must review the employee’s existing access.

Access that is no longer required must be removed or changed.

### Contractor Access

Contractor and vendor accounts must include an expiration date based on the expected end of the contract or assignment.

Account extensions must receive additional approval.

### Employee Termination

For routine departures, access must be disabled at the effective termination time or no later than the employee’s final working day.

For involuntary or high-risk terminations, access must be disabled immediately or before the termination meeting when appropriate.

Human Resources, the manager, and IT must coordinate the removal of access.

### Periodic Access Reviews

Managers and system owners must review access to critical systems every quarter.

The review must identify:

- Inactive accounts
- Terminated-user accounts
- Unnecessary privileged access
- Access that does not match current job responsibilities
- Contractor accounts that have passed their expiration dates

Access issues must be documented and assigned to the appropriate owner for correction.

### Logging and Monitoring

Systems containing sensitive information must record important access activity where technically supported.

Logs may include:

- Successful and failed login attempts
- Administrative actions
- Account creation and removal
- Permission changes
- Unusual access activity

Security logs must be protected from unauthorized changes and reviewed according to the organization’s monitoring procedures.

## Policy Exceptions

Policy exceptions must include:

- The reason for the exception
- The affected system
- The associated risk
- Compensating controls
- An expiration or review date
- Approval from an authorized owner

Exceptions must be reviewed before their expiration date.

## Evidence an Analyst Could Request

An analyst could request the following evidence to evaluate whether the policy is being followed:

- Approved access-request tickets
- Manager approvals
- User-account listings
- MFA configuration screenshots
- Human Resources termination records
- Account-disable timestamps
- Quarterly access-review reports
- Privileged-access reports
- Authentication logs

The evidence would need to be reviewed before concluding that the controls are operating effectively.

## Related Requirements

This practice policy supports concepts found in:

- HIPAA Security Rule access-control requirements
- HIPAA workforce security and termination procedures
- NIST Cybersecurity Framework identity management and access control
- Principle of least privilege
- Role-based access control

## Skills Practiced

- Policy writing
- Access-control documentation
- Joiner, mover, and leaver processes
- Least-privilege concepts
- Evidence identification
- Control ownership
- Access-review planning
- Exception documentation

## Project Disclosure

This is an educational portfolio project based on a fictional organization. I developed and edited this policy with AI-assisted guidance and reviewed the content for my own understanding.

It does not represent a policy approved by an actual company, a professional audit, or legal advice. No real patient information, employee records, credentials, or confidential company data are included.
