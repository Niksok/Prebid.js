# Overview

Module Name: Visx Bidder Adapter
Module Type: Bidder Adapter
Maintainer: 

# Description

Module that connects to Visx demand source to fetch bids.

# Test Parameters
```
    var adUnits = [
           {
               code: 'test-div',
               sizes: [[300, 250]],
               bids: [
                   {
                       bidder: "visx",
                       params: {
                           uid: '903536',
                           priceType: 'gross' // by default is 'net'
                       }
                   }
               ]
           },{
               code: 'test-div',
               sizes: [[728, 90]],
               bids: [
                   {
                       bidder: "visx",
                       params: {
                           uid: 903537,
                           priceType: 'gross'
                       }
                   }
               ]
           }
       ];
```