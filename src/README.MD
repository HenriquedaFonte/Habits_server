Habits API

Overview
The Habits API allows users to create, read and update habits. Habits can be tracked by date and have a title and a completion status.

Endpoints
GET /summary: Retrieve a list of all habits
GET /habits/:id: Retrieve a specific habit by its ID
GET /day: Retrieve a specific day
POST /habits: Create a new habit
PATCH /habits/habitId/toggle: check or uncheck an existing habit


Data Model
A habit consists of the following fields:

id (integer): The ID of the habit
title (string): The title of the habit
completion_status (boolean): The completion status of the habit
created_at (date): The date of the habit