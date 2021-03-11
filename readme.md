# Siametrics UX/UI Testing

## Requirements

1. Build a **Mobile Transportation Management System** for Driver.
1. The key feature is Manage Driver Task.
1. One day task of driver could be picking up box at warehouse, droping box at Distribution center, picking up box at Distribution center, droping box at Customer house, and Verifying by customer signing on Driver phone.
1. Every steps of picking or droping, the driver must scans all boxs for confirming of box reception.
1. Example of tasks in 1 day 
```
tasks = [
  {
    number_of_box: 10,
    location: {
      lat: 100.123123,
      lng: 23.231233,
      name: "A",
      type: "WAREHOUSE",
    },
    type: "PICK",
    time: "10:00",
  },
  {
    number_of_box: 15,
    location: {
      lat: 101.123123,
      lng: 24.231233,
      name: "B",
      type: "WAREHOUSE",
    },
    type: "PICK",
    time: "10:30",
  },
  {
    number_of_box: 5,
    location: {
      lat: 101.123123,
      lng: 25.231233,
      name: "C",
      type: "WAREHOUSE",
    },
    type: "PICK",
    time: "10:40",
  },
  {
    number_of_box: 10,
    location: {
      lat: 100.323123,
      lng: 25.231233,
      name: "D",
      type: "DC",
    },
    type: "DROP",
    time: "11:00",
  },
  {
    number_of_box: 5,
    location: {
      lat: 100.323123,
      lng: 25.231233,
      name: "D",
      type: "DC",
    },
    type: "PICK",
    time: "11:10",
  },
  {
    number_of_box: 20,
    location: {
      lat: 102.323123,
      lng: 27.231233,
      name: "E",
      type: "DC",
    },
    type: "DROP",
    time: "12:00",
  },
  {
    number_of_box: 5,
    location: {
      lat: 100.323123,
      lng: 25.231233,
      name: "F",
      type: "DC",
    },
    type: "DROP",
    time: "14:00",
  },
];
```


## Submission
1. Reports of User Research, Competitor Research.
1. Journey map, Wireframe Design, UI Design.

## Good luck !!
