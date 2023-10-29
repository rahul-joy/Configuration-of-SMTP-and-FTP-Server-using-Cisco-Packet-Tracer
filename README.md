# Configuration-of-SMTP-and-FTP-Server-using-Cisco-Packet-Tracer
Configuration of SMTP and FTP Server using Cisco Packet Tracer

<div class="bee-page-container">
		<div class="bee-row bee-row-1">
			<div class="bee-row-content">
				<div class="bee-col bee-col-1 bee-col-w12">
					<div class="bee-block bee-block-1 bee-image"><img alt="" class="bee-center bee-autowidth" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEizf4mv_V7sg9PV1koAtxHHuybn1F5CoGjXqSXUeXmKoV-x1zPwcrx_-G51uA-cXO6QjO8LGT8XeRO6KU0S2Or22Yy0RC5SmkNC910TO_QMIvzAPzHZfdZFyhe4CImte3dfkUDFNrAKlYX0la5ZUFv8w4wp4vBt2lg9vGKnAKlyrw1MrGwc7GVfyVoNPd0/s1360/Untitled%20design%20(1).jpg" style="max-width:1200px;" /></div>
				</div>
			</div>
		</div>
		<div class="bee-row bee-row-2">
			<div class="bee-row-content">
				<div class="bee-col bee-col-1 bee-col-w12">
					<div class="bee-block bee-block-1 bee-image"><img alt="" class="bee-center bee-autowidth" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhezo1PkIWE2O3Jd6r4OXCadUpDdf72Q1UHs1rTMdqnC4pZ8Q4phCJE6tndBzJPpDgi0_V579Kf6Jg0pq8ku7_AvO1dF2-bjudmtQBXcq-h4RDGp6TuBT5YdtGhQ4Q_83zALc5PHfT2qa671X_u0ZZZRc3OPw64EJBFD74h5SqlXUpmVxgO8WE1seyYAiU/s779/1.png" style="max-width:767px;" /></div>
				</div>
			</div>
		</div>
		<div class="bee-row bee-row-3">
			<div class="bee-row-content">
				<div class="bee-col bee-col-1 bee-col-w12">
					<div class="bee-block bee-block-1 bee-paragraph">
						<p><strong>1. TITLE OF THE LAB REPORT EXPERIMENT:</strong> Configuration of SMTP and FTP Server<br /><strong>2. OBJECTIVES/AIM</strong><br />            • To learn about step-by-step configuration of FTP Server &amp; SMTP Server using Cisco Packet Tracer.<br />            • To learn how to send email from end-host to end-server.<br />            • To learn how to upload a file to the FTP Server.<br />            • To learn how to rename and delete a file in an FTP server.<br />            • To learn how to download a file from the FTP Server.<br /><strong>3. PROCEDURE / ANALYSIS / DESIGN</strong><br />            1. Create a network by setting up all the necessary devices in Cisco Packet Tracer.<br />            2. Configure static IP addresses on the PC, Laptop, Server, and other devices.<br />            3. For FTP Server Configuration, click on the Server and go to the FTP option then at the<br />                right side turn on the FTP server. After that, provide a username and password for the<br />                server. Then, provide the permission to access “Write”, “Read”, “Delete”, “Rename”,<br />                “List” options.<br />            4. Now, an FTP client is built in the PC to send files to an FTP server configured in the<br />               Server. The FTP client can be used to read, write, delete and rename files present in the<br />               FTP server. For accessing the file, there are existing some commands which are listed<br />               below:<br />                        (a) put - used to upload a file to the server. For example: put ABC.txt<br />                        (b) get - used to get(download) a file from the server. For example: get ABC.txt<br />                        (c) delete - to delete a file in the FTP directory with the server. For example: delete ABC.txt<br />                        (d) rename – used to rename a file. Command: rename “Old file name” “New file<br />                             name” For example: rename ABC.txt, myFile.txt, etc.<br />                        (e) dir – use to see the existing listed files in the FTP server directory<br />                        (f) quit – use to close the connection<br />            5. For DNS Server Configuration, click on the server then go to the IP Configuration. Put<br />                your IP, Default Gateway which is your router IP, and DNS Server option will be 0.0.0.0<br />                for DNS Server Configuration</p>
					</div>
					<div class="bee-block bee-block-2 bee-image"><img alt="" class="bee-center bee-autowidth" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEizf4mv_V7sg9PV1koAtxHHuybn1F5CoGjXqSXUeXmKoV-x1zPwcrx_-G51uA-cXO6QjO8LGT8XeRO6KU0S2Or22Yy0RC5SmkNC910TO_QMIvzAPzHZfdZFyhe4CImte3dfkUDFNrAKlYX0la5ZUFv8w4wp4vBt2lg9vGKnAKlyrw1MrGwc7GVfyVoNPd0/s1360/Untitled%20design%20(1).jpg" style="max-width:1200px;" /></div>
					<div class="bee-block bee-block-3 bee-paragraph">
						<p><strong>4. IMPLEMENTATION</strong><br />            1. Build the network topology.</p>
					</div>
					<div class="bee-block bee-block-4 bee-image"><img alt="" class="bee-center bee-autowidth" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEizf4mv_V7sg9PV1koAtxHHuybn1F5CoGjXqSXUeXmKoV-x1zPwcrx_-G51uA-cXO6QjO8LGT8XeRO6KU0S2Or22Yy0RC5SmkNC910TO_QMIvzAPzHZfdZFyhe4CImte3dfkUDFNrAKlYX0la5ZUFv8w4wp4vBt2lg9vGKnAKlyrw1MrGwc7GVfyVoNPd0/s1360/Untitled%20design%20(1).jpg" style="max-width:1200px;" /></div>
					<div class="bee-block bee-block-5 bee-paragraph">
						<p>2. Configure static IP addresses on the PC, Laptop, DNS server, Mail Server and FTP server.<br />            a) Click the device and go to the Desktop tab &gt; IP Configuration.<br />                        <strong>For Gateway:</strong> 192.168.1.2<br />                        <strong>For DNS Server:</strong> Set 192.168.1.4 as IP address and 255.255.255.0 as Subnet Mask<br />                        <strong>For Mail Server:</strong> Set 192.168.1.1 as IP address and 255.255.255.0 as Subnet Mask<br />                        <strong>For FTP Server:</strong> Set 192.168.1.3 as IP address and 255.255.255.0 as Subnet Mask<br />                        <strong>For David: </strong>Set 192.168.1.10 as IP address and 255.255.255.0 as Subnet Mask.<br />                       <strong> For Jon:</strong> Set 192.168.1.11 as IP address and 255.255.255.0 as Subnet Mask.<br />                      <strong>  For Jerry: </strong>Set 192.168.1.12 as IP address and 255.255.255.0 as Subnet Mask.</p>
						<p><br />                       <strong> For Gateway:</strong> 192.168.2.1<br />                        <strong>For DNS Server:</strong> Set 192.168.2.3 as IP address and 255.255.255.0 as Subnet Mask<br />                        <strong>For Mail Server:</strong> Set 192.168.2.3 as IP address and 255.255.255.0 as Subnet Mask<br />                       <strong> For Jenny:</strong> Set 192.168.2.13 as IP address and 255.255.255.0 as Subnet Mask.<br />                      <strong>  For Loara:</strong> Set 192.168.2.14 as IP address and 255.255.255.0 as Subnet Mask.</p>
					</div>
					<div class="bee-block bee-block-6 bee-image"><img alt="" class="bee-center bee-fixedwidth" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjukKhFue8AcKQZlSIWR-9akTj5sNWncYAw1UZcnSjoi4JCZeOoM-B6dpBWoIi2VoZrJl9LRiA-VSmQf9KQBN7Wytv5yRgVBQv4CP4buUSkNKS2XAKVaV0QeMZlwewzai-Kfw7xvnuVD8juEYAd6soj-TB_DDRUh4nG4wWxlYD_8KG0XxLM7VosVwv81sQ/s1372/2.png" style="max-width:960px;" /></div>
					<div class="bee-block bee-block-7 bee-paragraph">
						<p>3. Click on the “FTP Server” and then clicking on the “Services” option to FTP server configuration.<br />           (a) Click on the FTP option then at the right side click On to enable the FTP server.<br />           (b) Provide a username and password and then click on “Write”, “Read”, “Delete”,<br />                “Rename”, “List” options. At last, click the “Add” button (Figure 4).<br />           (c) Now, an FTP client is built in the PC to send files to an FTP server configured in the<br />                Server. The FTP client can be used to read, write, delete and rename files present in the FTP server</p>
					</div>
				</div>
			</div>
		</div>
		<div class="bee-row bee-row-4">
			<div class="bee-row-content">
				<div class="bee-col bee-col-1 bee-col-w12">
					<div class="bee-block bee-block-1 bee-icons" id="beepro-locked-footer">
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
