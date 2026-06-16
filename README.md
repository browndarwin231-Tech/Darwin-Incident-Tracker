# Darwin Incident Tracker

A Python cybersecurity project that records and tracks security incidents using a simple incident management system.

## Features

- Add security incidents
- View recorded incidents
- Store incidents during program execution
- Beginner-friendly Python code
- Introduces incident management concepts

## Code

```python
incidents = []

while True:
    print("\n=== Incident Tracker ===")
    print("1. Add Incident")
    print("2. View Incidents")
    print("3. Exit")

    choice = input("Choose an option: ")

    if choice == "1":
        incident = input("Enter incident: ")
        incidents.append(incident)
        print("Incident Saved")

    elif choice == "2":
        print("\nRecorded Incidents:")

        if len(incidents) == 0:
            print("No incidents recorded")
        else:
            for item in incidents:
                print("-", item)

    elif choice == "3":
        print("Goodbye")
        break

    else:
        print("Invalid Option")

print("Created by Darwin Brown")
```

## Example

```
=== Incident Tracker ===

1. Add Incident
2. View Incidents
3. Exit

Choose an option: 1

Enter incident: Failed login from unknown IP

Incident Saved
```

## Skills Used

- Python
- Lists
- Loops
- User Input
- Conditional Statements
- Incident Tracking
- Cybersecurity Fundamentals

## Future Improvements

- Save incidents to a file
- Add incident severity levels
- Add timestamps
- Search incidents
- Export incident reports

## Author

Darwin Brown
