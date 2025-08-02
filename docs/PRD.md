# Product Requirements Document: Doodle Search Engine (v1.0)

**Author:** Mert Furkan Ergüden
**Status:** In Development
**Last Updated:** 01.08.2025

## 1. Overview & Vision
Doodle is a project to build a modern, minimalist web search engine from scratch. Our vision is to demystify search technology by combining it with product management principles in a transparent, manageable project.

## 2. The Problem
Existing major search engines can sometimes be overwhelming with ads and complex algorithms. From a product manager's perspective, there's a lack of practical, hands-on projects to understand the core technical components of a search engine (crawling, indexing, ranking) by building a simplified model.

## 3. Target Audience
*   **Primary:** Developers and aspiring Product Managers who are technically curious and want to learn how a search engine works.
*   **Secondary:** Users looking for a simple, ad-free, and straightforward search experience.

## 4. Goals & Success Metrics
### Goals
*   Build a functional web app for basic text and (eventually) image search.
*   Document the process and decisions in a public blog series.
*   Open-source the entire codebase and documentation on GitHub.

### Success Metrics
*   **Product:** Successful deployment of the application to a public server.
*   **Personal Growth:** A minimum of 5 detailed blog posts and 100 meaningful GitHub commits documenting the journey.

## 5. MVP Scope: Core Search Functionality
This PRD covers the MVP (Minimum Viable Product). The goal is to deliver a working core search engine.

### User Stories (Must-Haves)
*   **US-1:** As a user, I want to enter a search query on a homepage so that I can find relevant information.
*   **US-2:** As the system, I want to crawl a predefined set of websites so that I can gather content to be searched.
*   **US-3:** As the system, I want to store and index the crawled data in a database so that it can be retrieved quickly.
*   **US-4:** As a user, I want to see a list of relevant results based on my query on a search results page.

### Out of Scope (Won't Haves - for now)
*   Image search
*   Video, news, or map tabs
*   User accounts or personalization
*   Advertisements
*   Advanced ranking algorithms (e.g., PageRank)