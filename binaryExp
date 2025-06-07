for i in {64..100}; do   echo "[*] Sending $i-byte payload";   head -c $i < /dev/zero | tr '\0' 'A' | ./birds; done
