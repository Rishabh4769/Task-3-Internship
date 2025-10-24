# 🧩 Task 3 — Basic Vulnerability Scan (OpenVAS / GVM)

A cybersecurity lab task performed to understand **basic vulnerability scanning** using **OpenVAS (Greenbone Vulnerability Manager)**.

---

## 🎯 Objective
Perform a vulnerability scan using OpenVAS on:
1. **macOS Host (real IP)**
2. **Kali Linux Virtual Machine**

and analyze the scan reports to identify exposed services, open ports, and potential CVEs.

---

## 🧠 Tools Used
- **OpenVAS (GVM)**
- **Kali Linux VM**
- **macOS Host Machine**
- Web Browser (for Greenbone web UI)
- Local Network for inter-system scanning

---

## ⚙️ Setup Summary
1. Installed GVM on Kali using:
   ```bash
   sudo apt install gvm
   sudo gvm-setup
   sudo gvm-start
   ```

2. Accessed GVM UI: https://localhost:9392

3. Created separate targets for macOS and Kali using their real IPs.

4. Performed Full and Fast scan for each target.

5. Exported reports (HTML + screenshots).

---

## 🖥️ Scan Results

| System Scanned | IP Type | Vulnerabilities | Exposed Ports | Result |
|----------------|---------|-----------------|---------------|--------|
| macOS Host | Real IP (192.168.x.x) | None | 0 | ✅ Secure |
| Kali Linux VM | Real IP (192.168.x.x) | None | 0 | ✅ Secure |

