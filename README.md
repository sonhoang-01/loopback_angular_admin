# Son.H test - LoopBack simple admin application
The project is generated by [LoopBack](http://loopback.io).

## Problem
  The Problem related to Task-PeddlerFullStack document

## Solution
  1. Get starting with loopback https://docs.strongloop.com/display/public/LB/Create+a+simple+API
    - Start a simple app ```slc loopback```
    - Create models ```slc loopback:model```
    - Wait, by default loopback provide db:memory, so how to connect to mongo?
  2. Work with mongodb https://docs.strongloop.com/display/public/LB/MongoDB+connector
    - ```npm install loopback-connector-mongodb --save```
    - Create models again but mongodb
  3. Loopback client by default return a text to inform that server worked, so how to bring up client to work with Angular?
    - The same of website struct is require static so go to https://docs.strongloop.com/display/public/LB/Add+a+static+web+page to learn

  After that all are ok. We have a great loopback restful API support full feature for $resource.

  Quickly knowledge at https://docs.strongloop.com/display/public/LB/AngularJS+JavaScript+SDK

  Enjoy and develop our angular app that dependence by your angular experiences skill.

