<?php

  $_customer = $_POST["customer"];
  $_produk = $_POST["produk"];
  $_jumlah = $_POST["jumlah"];

  if ($_produk == "Tv") {
      $harga = 4200000;
  }elseif($_produk == "Kulkas"){
    $harga = 3100000;
  }elseif ($_produk == "Mesin Cuci") {
    $harga = 3800000;
  }

  echo "Nama Customer : " . $_customer;
  echo "<br/> Produk Pilihan : " . $_produk;
  echo "<br/> Jumlah Beli : " . $_jumlah;
  echo "<br/> Total Belanja : " . $harga * $_jumlah;

?>