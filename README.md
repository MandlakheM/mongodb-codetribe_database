# mongodb-codetribe_database

This README outlines the specific MongoDB shell commands used to create the Codetribe project outcomes.

## Starting the MongoDB Shell (Mongosh)
To start the MongoDB shell:

Open a terminal or command prompt.
Run the following command to start the MongoDB shell:

``mongosh``

## To create the Database

``use Codetribe``

## To create the Collections

``db.createCollection("Facilitators")``

``db.createCollection("Trainees")``

``db.createCollection("Projects")``

## Inserting documents to the Facilitators collection

``db.Facilitators.insertOne({
  name: "Mahlatse Chommie",
  location: "Soweto",
  course: "full stack web dev"
})``

## Inserting documents to the Trainees collection

``db.Trainees.insertOne({
  name: "Sphelele",
  location: "soweto",
  facilitator: "mahlatse"
})``

## Inserting documents to the Projects collection

``db.Projects.insertOne({
  name: "codetribe database",
  course: "mongodb",
  lesson: "basics of mongo"
})``

## Viewing all documents in a collection

``db.Facilitators.find()``

``db.Trainees.find()``

``db.Projects.find()``

## To list all collections in the current database

``show collections``
