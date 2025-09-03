SERVER=("10.1.10.5" "10.1.10.22")  # <-- change with your sever IPs

for server in "${SERVER[@]}"; do
        echo "Clear cache memory $server"
        ssh username@"$server" 'echo 3 | sudo tee /proc/sys/vm/drop_caches'

done

echo "Lets drink some Coffee!"
