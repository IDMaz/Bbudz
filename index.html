<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Absensi TPQ B</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f7fc;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .form-container {
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 10px;
            width: 100%;
            
        }

        h2 {
            text-align: center;
            color: #333;
            margin-bottom: 20px;
        }

        .form-group {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 15px;
            border-bottom: 1px solid #f0f0f0;
            padding-bottom: 10px;
        }

        label {
            font-size: 16px;
            color: #555;
            margin-right: 0px;
            flex: 0.8;
        }

        .radio-buttons {
            display: flex;
            justify-content: space-evenly;
            flex: 1;
        }

        .radio-buttons input[type="radio"] {
            margin-right: 5px;
            margin-left: 5px;
        }

        button {
            width: 100%;
            padding: 15px;
            background-color: #4CAF50;
            color: white;
            font-size: 18px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #45a049;
        }

        /* Media Query untuk tampilan lebih kecil */
        @media (max-width: 250px) {
            .form-container {
                padding: 10px;
            }

            .form-group {
                flex-direction: column;
                align-items: flex-start;
            }

            .radio-buttons {
                width: 100%;
                justify-content: flex-start;
                flex: 0.6;
            }

            .radio-buttons input[type="radio"] {
                margin-right: 20px;
            }

            button {
                font-size: 16px;
                padding: 12px;
            }
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2>Absensi TPQ B</h2>
        <form id="attendanceForm">
            <!-- Siswa 1 sampai 25 (contoh) -->
            <div id="studentsContainer">
                <!-- Siswa akan digenerate menggunakan JavaScript -->
            </div>

            <button type="submit">Kirim Pesan WhatsApp</button>
        </form>
    </div>

    <script>
        // Daftar nama siswa
        const students = [
            'Abrisam Haziq Musyaffa', 'Aida Revalina Kusnandar', 'Alesha Syandana Sahla', 'Alifiya Azzahra', 'Aqilla Fariza Mufia',
            'Arkhan Dzaky Arindra', 'Athar Mauza Ramadhan', 'Dera Fauzil', ' Fahrul Muazzam Maliq', 'Fathiya Adzkya Tahira',
            'Fatimah Asma Usamawati', 'Hafidz Ahmad Anshori', 'Hafiz Djalu Sopiyan', 'Jelita Ayunda Putri', 'Muazam Gibran Al Thavarizqi',
            'Muhamad Giandra Verdianto', 'Muhammad Arshaka Kenzi', 'Nia Qalesya Mukti', 'Rafassya Alexi Pratama', 'Reinand Kinza Rivandra',
            'Thasa Aulia'
        ];

        // Menambahkan form input siswa secara dinamis
        const studentsContainer = document.getElementById('studentsContainer');
        students.forEach((student, index) => {
            const formGroup = document.createElement('div');
            formGroup.classList.add('form-group');
            formGroup.innerHTML = `
                <label for="siswa${index + 1}">${student}:</label>
                <div class="radio-buttons">
                    <input type="radio" name="siswa${index + 1}" value="Hadir" checked> Hadir
                    <input type="radio" name="siswa${index + 1}" value="Absen"> Absen
                    <input type="radio" name="siswa${index + 1}" value="Izin"> Izin
                    <input type="radio" name="siswa${index + 1}" value="Sakit"> Sakit
                </div>
            `;
            studentsContainer.appendChild(formGroup);
        });

        // Fungsi untuk mendapatkan tanggal hari ini dalam format dd-mm-yyyy
        function getTodayDate() {
            const today = new Date();
            const day = String(today.getDate()).padStart(2, '0');
            const month = String(today.getMonth() + 1).padStart(2, '0'); // Bulan mulai dari 0
            const year = today.getFullYear();
            return `${day}-${month}-${year}`;
        }

        // Fungsi untuk mengubah format tanggal menjadi dd Mmm yyyy (contoh: 20 Nov 2024)
        function formatTanggal(inputDate) {
            const [day, month, year] = inputDate.split('-');

            const bulan = [
                'Jan', 'Feb', 'Mar', 'Apr', 'Mei', 'Jun', 
                'Jul', 'Agu', 'Sep', 'Okt', 'Nov', 'Des'
            ];

            return `${day} ${bulan[parseInt(month) - 1]} ${year}`;
        }

        // Fungsi untuk mengirim data ke Webhook dan WhatsApp
        async function sendWebhookData(data) {
            const webhookUrl = "https://hook.us2.make.com/y58e68hc4qi70ijq5uqpebjdd9l1jjo0"; // Ganti dengan URL webhook dari Make.com

            try {
                const response = await fetch(webhookUrl, {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json',
                    },
                    body: JSON.stringify(data),
                });

                if (!response.ok) {
                    throw new Error('Webhook request failed');
                }
                console.log('Webhook sent successfully');
            } catch (error) {
                console.error('Error sending webhook:', error);
            }
        }

        // Mengirim pesan melalui WhatsApp
        document.getElementById('attendanceForm').addEventListener('submit', async function (e) {
            e.preventDefault();

            let message = `Assalamu'alaykum wr wb. Selamat sore ibu wali santri TPQ B. Berikut daftar kehadiran santri:\n *${formatTanggal(getTodayDate())}* \n\n*Note*: *Izin kehadiran dilaksanakan sebelum kegiatan belajar dimulai dan atau selama kegiatan belajar berlangsung. Apabila izin setelah kegiatan belajar selesai, dianggap absen/tidak hadir karena presensi dilaksanakan saat proses kegiatan belajar dikelas. Atas pengertiannya, Terima kasih 🙏🏻.* \n\n`;

            const hadir = "✅";  
            const absen = "❌";   
            const sakit = "❌sakit";   
            const izin = "❌izin";   

            const attendanceData = [];

            students.forEach((student, index) => {
                const status = document.querySelector(`input[name="siswa${index + 1}"]:checked`).value;

                let icon;
                if (status === "Hadir") {
                    icon = hadir;
                } else if (status === "Absen") {
                    icon = absen;
                } else if (status === "Sakit") {
                    icon = sakit;
                } else if (status === "Izin") {
                    icon = izin;
                }

                message += `${index + 1}. ${student}: ${icon}\n`;

                // Menyimpan data untuk dikirim ke webhook
                attendanceData.push({
                    name: student,
                    status: status
                });
            });

            message += "\nTerima kasih.";

            // Kirim data ke webhook dan WhatsApp
            await sendWebhookData({
                date: getTodayDate(),
                attendance: attendanceData
            });

            // Kirim pesan WhatsApp
            const phoneNumber = "6285730872024"; // Ganti dengan nomor tujuan
            const params = new URLSearchParams();
            params.set('phone', phoneNumber);
            params.set('text', message);

            const url = `https://api.whatsapp.com/send?${params.toString()}`;
            window.location.href = url;
        });
    </script>
</body>
</html>
