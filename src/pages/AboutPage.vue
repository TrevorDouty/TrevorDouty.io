<template>
  <div class="container-fluid">
    <div class="about">
      <div class="row justify-content-center">
        <div class="col">
          <h1 class="text-center py-3">
            Trevor Douty
          </h1>
          <p>I graduated form Northwest Nazarene University with a degree in biology. After pursuing work in the medical field I quickly realized it wasn't the life for me. Through self study and attending a coding bootcamp I became a software developer. I am proficient in the following languages and source control.</p>
        </div>
      </div>
      <div class="row pt-5">
        <div class="col text-center">
          <img class="small px-4" src="https://www.iconninja.com/files/840/443/663/logo-icon.png" alt="">
          <img class="small pr-4" src="https://cdn4.iconfinder.com/data/icons/iconsimple-programming/512/css-512.png" alt="">
          <img class="small pr-4" src="https://raw.githubusercontent.com/themedotid/bootstrap-icon/HEAD/docs/bootstrap-icon-css.png" alt="">
          <img class="small pr-4" src="https://www.devexhub.com/wp-content/uploads/2019/12/javascript-icon-png-23.png" alt="">
          <img class="small pr-4" src="https://uxwing.com/wp-content/themes/uxwing/download/07-design-and-development/vue-js.png" alt="">
          <br>
          <img class="small px-4" src="https://cdn.iconscout.com/icon/free/png-512/node-js-1174925.png" alt="">
          <img class="small pr-4" src="https://doc.octoperf.com/monitoring/create-connection/mongodb/img/mongodb-logo.png" alt="">
          <img class="small pr-4" src="https://cdn.iconscout.com/icon/free/png-512/mysql-19-1174939.png" alt="">
          <img class="small pr-4" src="https://cdn.iconscout.com/icon/free/png-512/csharp-1-1175241.png" alt="">
          <img class="small pr-4" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAh1BMVEX///8AAABVVVX09PT39/f7+/vR0dHe3t7w8PBlZWXGxsbo6OigoKDn5+fW1tacnJx0dHSnp6e+vr6UlJR+fn5gYGAVFRVKSkrS0tJcXFzLy8uwsLCGhoaNjY3c3Nw7OzszMzMkJCRFRUUUFBQrKytycnJAQECtra0cHBwLCws3NzcvLy97e3sXKeo2AAAKi0lEQVR4nO1d6XqiMBTVIi64o9YqLkVrq+28//ON1nZEuTc5CVmY7+P8lpgDyc3dU6tVqFChQoUKFSoYQXfTjJLeZDUdXTFdTXpJ1Nx0fU+sOMJmvJ5tj3UOx8/ZOmmGvqeph2DZ6zyz1O5x6vSWge8JK6EdrecguRvm6+g/WbWt3tNJmd7Pt3zqtXxPX4bWJNVk94t0svFNgkd3+FWQ3hVfw75vKhTCeGaE3hWLuGwCtl14dT4inbR9k8qgdTBM74pDWcTOS8cKvwtmTd/kzhgsrPG7YDHwzK9v7/v9ouNTsLan1vldMPUmc8a6uosqTmMv/AbvjvhdsHW/HUM3C/SGqWMVYMnbfLZwXDrkF66c87tg5ewztl69EKzXXx0pOWNP/C5wIVQDOzooioN1b0f/0yvB80q1rOJEnvldENkk2PPN7hs9ewT9HBJ5TG0RNOmmKIaZFX4NdReoPcwb5gkGW9+s7rA1fmo0zDgKzeHN8FcsHcF6/csoxeDNNx8CbwYXaqNce/AXW3NfsUxSNIu5KYLlOQcfYehcdO2vUIER7aYcuigHAzpqGawJEQpbGn3fDKQoaC8GvlwyOF6LHYt+XRYYDkUI+nQ64SjgnmoJB467Qbu1HB8sLuT9bhW/9M9/I44gaDsZQ+Hct7cXMX4yyusHz6PoX9ApFv7yVddVLHZafGR/2h+advMv4jsJIv7xSo/gUjzqY1Av3pmjV58+ngF/xL/XimmE4qw0QiVsGlqs+0n+AJAoHkeddSpRR0kBtjTBkUwzCSQPaSioA8mQTG5WtC/Ib8SEtGUJEeohVInRm7KaxDD321O6XYzW4ySOlsvmS3MZxXHSW3Xmb/m3MWcF/0TCcMs9yEF21j/xj3Zv+Rn7+WgYbdhEg6D1kqxmtzPpOeFHlVoAiud+W5aE8Ef0dHwRUtvpRwtKomh0o8n3Gvwj+rlY+zjjpJaxIbV6xW8smMSK+nA4GIolfleacKwkbOQ2k9UAEAWxgvUNFTtKnunkMm3gCrlC0cEHk50UdR3hXBTAUYtPCkjGKyXDBTpWUz5WORnWX8CxkHxDdCxzQNzS4E6UnjwXuJc0UBodZgtDvpnYMp8csOAQ5LNpIyPVh7YZPaKLpXoiio1MxVV4WSYB7Z2z6SUfKUyhkYyFfVAkGMNUbgqLfT7/sHedmYxmusgFBBpKc31coDFMacANjlMAC94kMPl3gazEL2+hM9g5IfYP4Dasy6U8nnPhtgwCd3G9igcCZfIZC7eZ5aAAvECs12CH4eVNWUi7EgJfpmIJkaLDuC/ZXaNTS0WjwIvUuVpaU9iKomWKZiWMnNHKAD4wRNkL4Gs6ut6EV6DSRuTLBUu1fKzRC8BSQIHnFMwsca51/wIVE7yrExRX/kpXQfV7zQ6AabfePmGt1sAYsjOUxeh+4LP6GFxlXEhBEtb+wadTSg/oFvsI2Gnop2L1F5g45U5E7Gm/LVYwcc/5TaEANew5t4MG5FTc0w+H0Ovxu0hrtRE0S9q0Q8IVbIaCM2DLlBY1kAUmNE1cAJOmdEIAdNbYqalSAVTiSWs1kB/RuTc/B2gj0h8CKhvxZVbc8IFMk86ugbILfQsaUPM6Uk9iW9h/4zjMhKL0kg30pHNCeUDzpNYadhw655MHNE8qrAIdpYw65BQQQ8rMhw78MjCEnEnUkQ/ZTmVgCBkIlP0EOfRPzvnkAX1DyrWPeXmc88kDmieVvY+VGTrnkwc0TyoVU5Lv/58xpDJ8MdPSOZ8cMEOdiqxg39B/Q0pMu6S+IcbQv+YNJL/W6X2IyVLn2c85YG4MSpZi7mRBvYAjYOFuysjH8kwcp9EQwL4EpdNAtrNKtrglYP1SqbWGrW/l4hvjwDJ+KHmB2Yd7PwHuG8BoPuUwxWx878cFdliQ0wRz9nwLU7C8nPLTSGpGfyEs6XIArEMA6WurYVXn744ZPaCBzZIO44Jtq/32vAfTMWifN5jo8EE+7Apg/isdtwCz//zGZsBkaFoeYokKft3eYKYCEz8Ek028LlM0/5XRS8CnfaabgLXwnEsQvQPAXzN/tKUTZx+gefr+7Au06ILLp4GbXvm6WQOVhWztIJyE6yVFuKaQB82Ke7j/ih8DA15jfPYk3CfYccHMD9BLzgQNefCyDR9nIt6nmXcIohpD3Yf+jfkgLhB1yMDbeDpPFA5SeG6CXH28cs1iT20GCt2LRPUWoK/mG26TFLG40RXC41qlJ5nL9Ci46KkuSy5UGckhRbik7gKxWx701f3A1Zmh1gVXolOmSoM5iWKEan2MXyXDKa2Hs5lhv5JU9VYbWX6oas/Zve36EuU2xtJaAuWueSubfpuNcitxuaMMr7f9RWrN0a9zc51cwDc02nR+Wol9NxRlwjeAvhjMkXj8FFw+feaYmBY5fb0rX5A8dMrSn27Om6296Qk2abo26Ntoa19MCwmFfPnTzZAQvtnd2AjJID7Atu4jMP9KXv3OxqoCYd7N23pZbLkOeoVa2YJma36F3HUUGkiKq3brpK+ROtVuJeuiDV5RPydhTXeybvKGvIzveX6YxAOQaGuZrDo77ZWZAeyrJl5levcwek5hpwjun5AAD4u9UI/f3a+IUURVAdjTK4GCk5OU1dvsNkZiHHiXbTPd7VX6jzH6d0bLBhxDXwp/aORiaKX6XeZIyOwruQNaJUSFt4HiodaYnfvHTMhDlvahFtxQ8PIxeFa0cbidcduLsv4GavpNULgvv7KFw1QjZq4hEK9T1YQGJR8YAfVQCueTyuRECVeWqiMO78FFQ0Ml5o68jLQRqOEnZcu/2NUKfDsTHiGzM7KJCjxFUeyARqF7pb609H1un2W3NHtUq1dEF9LdNP1hzBe6S+XYMBJJwx9egKCu3zZkSt/vZ9+jjIKjRnxR37jQD0kz8u2h+UcwfjQY3xOdXGn9OwgLhGuZbZZTAAeTW6fm+VDTlwF28sqjUISIDtuRocPWMoqjZgFPje79YMVitfT9nNr3Kwmh+Q3nBSdD21FWwmqaFlThajra/rZRpKfnhjKQvERKGxu9lLQYGomZkFq/hS4uOgwNhWhJIWc+iK/B0FjxB/nfximqMzSX6BqS6oaBa1zvoMzQpDAISOPtYLaOTZXhk9G/b9D3ZxhdqYoMi570jwhpijuD0V81huomtgwNZgLvPVOJmEoMbaS58Ik7u3WUtTbCTTzRecMqDC1dICIMx6Tzzmg06jz9lOlqDK/AUMfvBEHBMa0xOs7QYuInngiuMTjM0GpfB9hvqzE22i7dcovYAJyHxtDYyA5yBbFMJY2BIYamVUUSUExaY1yA4clR2VwAJCxpDCtneHB3L4o8gVFjUBnDk9POol2Z20hjTAnDjusGTpKjUWNEMUMPzY1CYYKbxoAihprXwxfFQDAnjeH40Wa+ilbPS5VN4tMYjGP46f6+zCw+mJiYxlA0w9R/b+ZcbM0kw1ff7XC+ESZE+EZjnDzDXez26jMBokd3o07fhUfZvPC7/x7RuncA6Dj9707Y/drvPRoUGslNz/nScmXeFvusPMvzHv3edbUu9N5/97oTn8bl+3wZdOOPRP98bsVJ5L9/aIUKFSpUqFChQoUKFSpUqFChjPgLwW2YO9Vgd+cAAAAASUVORK5CYII=" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutPage'
}
</script>
<style>
.small{
  height: 5%;
  width: auto;
}
</style>
