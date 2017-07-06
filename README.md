# openshift-egress-router-example

https://docs.openshift.com/container-platform/latest/admin_guide/managing_networking.html#admin-guide-limit-pod-access-egress-router

Create router pod - as cluster admin

Add openstack allowed address pairs (WITH MAC ADDRESS)

Create service

Tests

Tested access from container via egress router with FW rule to only allow egress router IP - PASS

Tested replicated egress router retains and can failover - FAIL cannot deploy

Tested detroying contring and rebuilding to see if MAC was retained - FAIL cannot deploy
