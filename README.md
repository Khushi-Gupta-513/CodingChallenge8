# CodingChallenge8

// Commit: "Create Employee class with properties and methods"
class Employee {
    constructor(name, salary, position, department) {
        this.name = name;
        this.salary = salary;
        this.position = position;
        this.department = department;
    }

    getDetails() {
        return `${this.name}, Position: ${this.position}, Salary: $${this.salary}`;
    }
}
