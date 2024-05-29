--

# Basic Ansible Project

This project aims to provide a basic Ansible setup for automating infrastructure management.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed:

- Ansible (version 2.16.7)
- Python (version 3.12.x)

## Getting Started

Follow these steps to set up the basic Ansible project:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/basic-ansible.git
    ```

2. Change into the project directory:

    ```bash
    cd basic-ansible
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Configure the inventory file:

    Update the `inventory.ini` file with the IP addresses or hostnames of your target machines.

5. Create the playbook:

    Create a new playbook file, e.g., `vm-setup-playbook.yml`, and define your desired tasks and configurations.

6. Run the playbook:

    Execute the playbook using the following command:

    ```bash
    ansible-playbook -inventory inventory/vm-setup-playbook/hosts vm-setup-playbook.yml
    ```

7. Verify the results:

    Check the output of the playbook execution to ensure that the desired tasks have been completed successfully.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).