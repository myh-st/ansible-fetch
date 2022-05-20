# ansible-fetch

    ansible-playbook -i inventory copy-file.yml

# Structure

    .
    ├── copy-file.yml
    ├── inventory
    ├── README.md
    └── result
        ├── hosts
        │   └── rhel-client
        │       └── hosts
        └── resolv
            └── rhel-client
                └── resolv.conf
