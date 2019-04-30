Place `semtech-packet-forwarder.service` file in `/lib/systemd/system` directory.

Run the following:

    systemctl daemon-reload
    systemctl enable semtech-packet-forwarder.service
    systemctl start semtech-packet-forwarder.service
