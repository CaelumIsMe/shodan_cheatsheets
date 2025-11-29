---

# Shodan Search Cheatsheet

---

## Search for Google or DNS
```shodan
google.com
8.8.8.8
```

---

## Search for Cameras
```shodan
title:camera
webcam has_screenshot:true
```

---

## Search for VoIP Devices
```shodan
device:"voip"
```

---

## Search for MySQL Servers
```shodan
product:MySQL
```

---

## Search for Directory Listings
```shodan
http.title:"Index of /"
```

---

## Search for Default Passwords
```shodan
"default password"
```

---

## Search for Laser Printer FTP Servers
```shodan
"Laser Printer FTP Server"
```

---

## Search for Hacked Devices
```shodan
hacked
```

---

## Search for Anonymous FTP Login
```shodan
anonymous@ login ok. port:"21"
"220" "230 Login successful." port:21
```

---

## Search for SMB Authentication Disabled
```shodan
port:"445" Authentication: "disabled"
"Authentication: disabled" NETLOGON SYSVOL -unix port:445
```
