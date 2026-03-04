# API IDOR Vulnerability

## Endpoint

GET /api/user/102

## Test

Change ID:

GET /api/user/101

## Result

The API returns another user's data without authorization checks.

## Impact

Unauthorized access to sensitive user data.

## Mitigation

Implement proper authentication and authorization checks.
