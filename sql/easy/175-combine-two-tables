-- LeetCode 175: Combine Two Tables
-- Difficulty: Easy
-- Approach: LEFT JOIN Person and Address on personId
-- Production Insight: Common pattern for reporting and CRM queries

SELECT p.firstName, p.lastName, a.city, a.state
FROM Person AS p
LEFT JOIN Address AS a
ON p.personId = a.personId;
