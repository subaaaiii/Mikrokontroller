
# Deep Learning - PID - iTCLab - IoT

## Menggupload program 05 ITCLab_PID untuk menghubungkan ITCLab dengan python (jupyter notebook):

<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/program.jpg" alt="" class="img-responsive" width="700">
</p>


## Library yang dibutuhkan di jupyter notebook:

<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/library.jpg" alt="" class="img-responsive" width="400">
</p>
 <p> membutuhkan library tambahan untuk mqtt client yaitu : from paho.mqtt import client as mqtt_client</p>
 
## import model untuk train data:

<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/model.jpg" alt="" class="img-responsive" width="400">
</p>

## setting parameter dan logic untuk mengevaluasi model:

<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/pid.jpg" alt="" class="img-responsive" width="400">
</p>


## opening connection python ke kit ITCLab:

<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/connection.jpg" alt="" class="img-responsive" width="400">
</p>

## proses epoch pid sampai error mendekati 0:

<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/epoch1.jpg" alt="" class="img-responsive" width="400">
</p>
<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/epoch2.jpg" alt="" class="img-responsive" width="400">
</p>
<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/epoch3.jpg" alt="" class="img-responsive" width="400">
</p>

## Pengaturan topik di IoT MQTT Panel:

<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/panel1.jpg" alt="" class="img-responsive" width="400">
</p>
<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/panel2.jpg" alt="" class="img-responsive" width="400">
</p>
Topik diatur dan didefinisikan berdasarkan topik yang di publish di program python:jupyter notebook

## Hasil grafik pemantauan di IoT MQTT Panel:

<p>
  <img src="https://github.com/subaaaiii/Mikrokontroller/blob/main/Deep%20Learning%20-%20PID%20-%20iTCLab%20-%20IoT/hasil.jpg" alt="" class="img-responsive" width="400">
</p>



