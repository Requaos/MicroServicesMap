# MicroServicesMap
A map of generic micro-services descriptions, specifications and needs

## Deployment: ##
#### Backend: ####
* API (nodeJS/Golang)
#### Frontend: ####
* Website
* Desktop App
* Android/iOS App

## Service Discovery: ##
* Check-in service

## Configuration: ##
* etcd

## Monitoring: ##
* Heartbeat service

## Authentication: ##
* Login
* Password checking and Token Provision

## Authorization: ##
#### User Management ####
* User Permissions
* Active Token Store
  Serves as a subnet bridge, only allowing requests with active tokens to travese this bridge

## Storage: ##
* Direct Storage
* Storage of link pools

## Circuit Breaking: ##
* Logic dependant on Heartbeat service
* Kill codes
