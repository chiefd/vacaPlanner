# TripStack – Vacation Planner
GOAL:
  -Simple web application to plan trips, by generating packing checklists, itinerary notes, and shareable trip details

Target User
  -Myself (solo planner for family trips, at least for now).

Core Problem
  -Trip planning is scattered across notes, texts, and memory. I want one place to organize everything and avoid forgetting gear.

MVP Features
  -Create/edit trips (name, dates, location, type)
  -Trip templates (camping, beach, city, etc.)
  -Auto-generated packing checklist
  -Itinerary notes
  -Reservations/links
  -Shareable read-only link

Non-Goals (v1)
  -No accounts/login
  -No mobile app
  -No maps/integrations
  -No complex collaboration

Tech Stack
  -FastAPI (Python)
  -Postgres
  -Docker
  -GitHub Actions (CI/CD)
  -Terraform + AWS ECS (deploy)

Success Criteria
  -I can create a trip in < 2 minutes
  -Deploys automatically on push
  -Accessible from phone
  -Has logs/metrics
  -Can demo + explain architecture in interviews
