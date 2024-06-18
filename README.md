=IFERROR(MID(A1, FIND("Control SSID", A1) + LEN("Control SSID") + 1, FIND(" ", MID(A1, FIND("Control SSID", A1) + LEN("Control SSID") + 1, LEN(A1)) & " ") - 1), "")
