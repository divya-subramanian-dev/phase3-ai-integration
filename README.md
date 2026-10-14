Phase 3 - AI Integration and RAG with Java

This repository contains my Phase 3 learning journey focused on AI-powered backend applications using Java and Spring Boot.
Objectives

    LLM Fundamentals
    Prompt Engineering
    Structured JSON Output
    Embeddings
    Vector Databases
    Retrieval Augmented Generation (RAG)
    pgvector
    Redis Caching
    Redis Rate Limiting
    Spring AI
    Cloud Deployment

Main Project
Document Q&A System (RAG)

A backend application that allows users to upload documents and ask questions using Retrieval Augmented Generation.

Flow:

Document Upload → Text Extraction → Chunking → Embeddings → Vector Storage → Retrieval → LLM Response → Answer with Sources
Tech Stack

    Java 21
    Spring Boot
    Spring AI
    PostgreSQL
    pgvector
    Redis
    OpenAI API / LLM API
    Maven
    Docker
    GitHub Actions

Features
Phase 3 Features

    LLM API Integration
    Prompt Templates
    Structured JSON Responses
    PDF Upload
    Document Chunking
    Embedding Generation
    Vector Search
    Retrieval Pipeline
    Source Citation
    Redis Cache
    Rate Limiting
    Cloud Deployment

Project Structure

src/
├── controller
├── service
├── repository
├── entity
├── dto
├── ai
├── rag
├── embedding
├── vectorstore
├── redis
├── config
└── test

Run Locally

mvn clean install
mvn spring-boot:run

Learning Progress

    LLM Basics
    Prompt Engineering
    Structured Output
    Embeddings
    pgvector
    RAG Pipeline
    Document Upload
    Redis Cache
    Rate Limiting
    Deployment

Future Enhancements

    Multi-document search
    Conversation memory
    Hybrid search
    Semantic ranking
    Streaming responses
