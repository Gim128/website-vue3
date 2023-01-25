<template>
    <div class="bg-gradient-to-r from-blue-100 via-blue-300 to-blue-500">
    <!-- <div class="max-w-full py-24 mx-auto sm:px-6 sm:py-32 lg:px-8">
      <div class="relative px-6 pt-16 overflow-hidden bg-gray-900 shadow-2xl isolate sm:rounded-sm sm:px-16 md:pt-24 lg:flex lg:gap-x-20 lg:px-24 lg:pt-0">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1024 1024" class="absolute top-1/2 left-1/2 -z-10 h-[64rem] w-[64rem] -translate-y-1/2 sm:left-full sm:-ml-80 lg:left-1/2 lg:ml-0 lg:translate-y-0 lg:-translate-x-1/2" aria-hidden="true">
          <circle cx="512" cy="512" r="512" fill="url(#759c1415-0410-454c-8f7c-9a820de03641)" fill-opacity="0.7" />
          <defs>
            <radialGradient id="759c1415-0410-454c-8f7c-9a820de03641" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(512 512) rotate(90) scale(512)">
              <stop stop-color="#7775D6" />
              <stop offset="1" stop-color="#E935C1" stop-opacity="0" />
            </radialGradient>
          </defs>
        </svg>
        <div class="max-w-md mx-auto text-center lg:mx-0 lg:flex-auto lg:py-32 lg:text-left">
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">Boost your productivity.<br />Start using our app today.</h2>
          <p class="mt-6 text-lg leading-8 text-gray-300">Ac euismod vel sit maecenas id pellentesque eu sed consectetur. Malesuada adipiscing sagittis vel nulla.</p>
          <div class="flex items-center justify-center mt-10 gap-x-6 lg:justify-start">
            <a href="#" class="rounded-md bg-white px-3.5 py-1.5 text-base font-semibold leading-7 text-gray-900 shadow-sm hover:bg-gray-100 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Get started</a>
            <a href="#" class="text-base font-semibold leading-7 text-white">Learn more <span aria-hidden="true">→</span></a>
          </div>
          <div class="flex items-center justify-center mt-10 gap-x-6 lg:justify-start">
            <a href="#" class="rounded-md bg-white px-3.5 py-1.5 text-base font-semibold leading-7 text-gray-900 shadow-sm hover:bg-gray-100 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Get started</a>
            <a href="#" class="text-base font-semibold leading-7 text-white">Learn more <span aria-hidden="true">→</span></a>
          </div>
        </div>
        <div class="relative mt-16 h-80 lg:mt-8">
          <img class="absolute top-0 left-0 w-[57rem] max-w-none rounded-md bg-white/5 ring-1 ring-white/10" src="https://apkdone.com/wp-content/uploads/2021/12/Google-Play-Store-poster.jpg" alt="App screenshot" width="1824" height="1080" />
        </div>
      </div>
    </div> -->
    <div class="max-w-full py-12 mx-auto sm:px-6 sm:py-12 lg:px-8">
    <div class="relative px-3 pt-8 overflow-hidden bg-gradient-to-r from-blue-100 via-blue-300 to-blue-500 shadow-2xl isolate sm:rounded-sm sm:px-6 md:pt-8 lg:flex lg:gap-x-6 lg:px-6 lg:pt-0">
    <div class="px-32 py-32">
      <div class="flex flex-row space-x-12">
        <div class="basis-1/2">
          <span class="text-4xl font-bold">
            Data to enrich your
          </span>
          <br>
          <div class="pt-1">
            <span class="text-5xl font-extrabold text-indigo-800">
              Your Business
            </span>
            <div class="pt-4">
              <span class="text-black font-normal">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur sapiente veritatis sit quod illo perspiciatis ullam perferendis libero sed voluptas qui quisquam, 
                labore beatae id corrupti itaque deserunt, provident praesentium?
              </span>
              <div class="pt-4"></div>
              <div class="flex items-center justify-center mt-6 gap-x-6 lg:justify-start">
                <a href="#" class="rounded-md bg-indigo-700 px-3.5 py-1.5 text-base font-semibold leading-7 text-white shadow-sm hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Get started</a>
                <a href="#" class="rounded-md bg-blue-600 px-3.5 py-1.5 text-base font-semibold leading-7 text-white">Learn more <span aria-hidden="true">→</span></a>
                <a href="#" class="rounded-md bg-indigo-700 px-3.5 py-1.5 text-base font-semibold leading-7 text-white shadow-sm hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Get started</a>
                <a href="#" class="rounded-md bg-blue-600 px-3.5 py-1.5 text-base font-semibold leading-7 text-white">Learn more <span aria-hidden="true">→</span></a>
              </div>
              
            </div>
          </div>
        </div>

        <div class="basis-1/2 px-0 py-0">
          <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxISEhUSEBMVFRUVFxUXFRUWFxcYFRUVFRUWFhUVFRUYHSggGBolGxUVITEhJSkrLi4uFx8zODMtNygtLisBCgoKDg0OGhAQGi0lHyUrLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLy0tLS0tLS0tKy0tLS0tLf/AABEIAKgBLAMBIgACEQEDEQH/xAAbAAABBQEBAAAAAAAAAAAAAAADAAECBAUGB//EAEUQAAEDAQQFCQQGCQMFAAAAAAEAAgMRBBIhMQVBUWGRBhMiMlJxgaHRFEKxwRVigpLh8AcXIzNTcpOissLS8RYkNHOD/8QAGgEAAwEBAQEAAAAAAAAAAAAAAAECAwQFBv/EADgRAAIBAgQDBwIFAQkBAAAAAAABAgMRBBIhMVFhcQUiQZGhsdGBwRMUMuHw8RVCUnKCkqLC0gb/2gAMAwEAAhEDEQA/APIQ1VraMvFXAFWt4y8fkqY2ikknolRSIZaOi24O8Pms9aWiBg7w+aa3Gi3cVUNWhd+ap0VMEDupi1FupqJACuprqNdTUQAG6ldRbqYtQAItUS1HLVEtQAAtUCEdwUCEgAlRRSE1EDsDomRKJUQFgaZEolRArA6JURKJqICxCiVFKiVEgGST0T0TAjRJEomogCFEqKdEyAIkKKnRMQgRBJToopAa4VW3avFWAVWtuQ8VTGVUydJSAxWnofJ3ePms1aGijg7vCaA0SVUVklVAVQwgUaJVTJATomomTAoAeiYpBOgCJCRCcpigATgoEIrkMpDBkKNFMhRogY1EqJ6JUQBGiVFKiaiAI0SonolRICFE9FKiSBEKKQCeiVEAJPRKieiYDUTEKdE1EBYHRRKLRRIQSDoo0UyooAvgoFq1KaFPqQAFJOkkOwld0acHeCoq3YMneCEFi+XYKsCpF2CECqAJVKqjVJFxkqpVUU4RcCdU15RCVUATTEqNUigBnIZUyoJDIlNRSolRAEKJUUrqV1AEaJ0qJUSHYaiaikQlRAiNEqKVEqIAhRPRPROgBgnolRPRMQkxT0SQAyg5TIUCECIKBRaKFECDBDlSCaRICKZJJIYlZshwKrI1myKaAtFyGClVRCYyaeqgkEATTqCeqBjqSg0okELnuDGNLnONA1oJJOwAYlAEVZsFglmfchY57jqaCT3mmQ35LqLFyVigAk0i+hzFnjIvn/2PGDO4VO8Itt5VFreasrGwR9mMUrvc7Nx3lQ5cBlCTkVMz/wAiaGLdevv+631QPoext/eWmZ26OFg83SH4KjPanONXElALkrsakuC9fk0X2fR2p1rPeYR/pKAbPYtRtHjzf+1AiLc3VpuNDxoUJta5o14msa6X9yL6p/8Aosvisg9+XxA+SjzVkOUjh9h6rSWUP8AsxzCDRO3Mf5uO34UPKf2mjfFis2qYeLXtViy6HjkcGxvjcdl/wqcclzLa12LrrHGLLCXuHSOL+8HoxnjxJUzuloeh2dTo4mbUqSjGKvKSlPTho5S39k+ALTGhW2WTm5xdJAILX3muB1tNcvNVodExyYseabaAgYa1QgD7TKTKanMnyAGz8CtC1aLfZ2iSN5xOWrDaqPInrLu7eGy9tiM3JyZv7u6/AGgcA+hr7pNdRBplTFZM0ZaaOBadhBB8109gYyVpeWh7jVxBxq5vXjx+qXEHOoG1WtHwc5KIq3431uh3SLTQnok4gYIu0b0o0qjUH3XtfdfKv1+hxSai6zS3JprSblR8Fz0lheDSleHzRGaZdXA1qfhdctf3KwCeiuHRU/8ACPl6pO0bMM46d7m+qq6IeDxC3py/2y+CnRIq4NHO2xDvkZ6o0ehJHVuuidQE0a8OwAqcksyNI9nYqW1NmXROnASVHCDIUEYhBQLYZRcVKqZyTAZMknQMZGgyKCjQ60AFUFNFsljkkNI2OdtIGA73HAeJTKjFydkrsCE61YdC0cWzy83T3WtEpr4ODeBK3NH8i45mudHbKBoq4vgutAGskSGinPHibSw9WO8Wcer+jprgLgG1NKFzWuIp2bwNM8xsCOdAyFxaCXYkAgdbeATXiFq6L5GWguBdFK5tfdjcK7rxwb3qXOLW52U8Biacs06enNpe7KVj0VLbJC6oaxtOdmdgxg1XiM3UyaMTuGK2jpeCxNMdgbVxFH2h4HOP2hvYbuHjU4rWm5MWuakTLkbWdWLJrK6yGuc6p7ThjrKoyfo1tut8J+275sSTuc9WhVcn3Ur818nJ2m2OeSXEklAvLqX8hLQ3N8ddzgfPBC/6OnODDfefdbdGGONbx3atee1Z4iWCrtXyP0+TmSoly6z9X9swrGd/Sjy3HnMVCTkLadUbh3viNeDhRVmRn+Xq/wCH2OW5yqTpWgZ47Pmuk/6PtLc4a/aZ/uVC0aFmacY6fbZ5dJGaPEpYTEP9NOT6JszILQBjjwKA+wvcQWipcK01+DcytRujJa4sJ+3H5dNasHIi2yM56KF10ZucW1woa9E1OQ1ak8yE8DiV+qnJdU16uxi8n9H3nlzxgyhcN/uN4gk7m70XlFaA83L1A03nb3O2nd8ytqx2QxMERuXsXPvk4yeAJoKAeFda5/SejHMcSL7xWtRd7/drXxAUJqUrnuV8NWwuAVKEHmm7zaTdrbR9v+XE3tCcm3sFXuArQ0AxyFBXir+m4I2xAOa94yaxgJc47taBo+SealbZZo67RK51d4DLg8Sp6Q5NyMPO2iRswyD47pZxa6g8VKzX1fkVfBKOTD0lKb2zuNnz70rvpFWMTQMUjJCGxvbWj2MoS5pacK0Fcfljv7DQWgDDN7Q8hrQXGOIEF4vggA0qBSvlksltoLeiKtGwLueSlv0eyMB1pAtLqVdLca5m0RNlcG1+sa9wTzt6GVfsuGDtVqyu77JWjf7JdOSTMjTsNwX5qMvCrWnrEbQ3MDeVyVphD8m0G05r0238lLHITI602mpqTI6MzM73TRgs/uCxpOSNiNTHpKJwGqnza4qctj08NisI42zNv/LK3ontxucNDZGt95x3DBiKSNQHjifNauk9Dxwkj2mEjUQ5wr4Oasd0sdbocHHdWnEoWp6UXSSsrL09yDymjixBADXHo3hnQ54o1qutFXa8hrWf7Ua9FNozruEJWla5lWuyuYakG6TgdRVZy07YxxaSCfrCuBpjULKLltF3Ph8ZQdKo1bR3a8/gZDU1BUcpBJySTkmCGTJ0yAEiwa0JX9FWQzOujLNx2BI0p05VJqEFdt2SN3kboGO0yA2mTm4A+KPDB0skzw1kbCftOcdTWnaF0/Kqzx2a02iCzxiNsLmNY0V96NpvEk1LiK4qpGyP2cWctdcEj5GvYKvjc9oGIqL2AaK4mlaZq/ymnbaJI7QHh75YIBMR/GjvscTgKEtuGhAzyCVRxcND2uy8JicP2ioTi1pJX8Grbp7Pw6ddDntH6ML3CutdtM+KztiY2jgBfcyuDn6i/aBjRqwLNMGYqkZX2glxN1mJ+s+gwAp3UXO02z6t4WFOSSXy/rwXE6STlhNW7BQbmANA7zqUfpKQ9K0zPf8AUDi1njrPksHng0XWtoN3z2od4npONBtPyGZ8EnG4fl6MPBLp87nSnlY5jbkLWhoyoAAO5oVSTStokxllIad9PutzPflvWEbXT920/wAzs/BuQ+KgGvf1nE/NPKRGnSveEdeNtfN/ubB0mxpq79ofrEhv3QaniinlbNS7H0dzGhg+CjoPk0Zm87VrYq05x7rrCRmGuPXP8octLSDrDZGFzb9ocMKNrHFe7Jkulzu7oqo0m9Uvsedi+08DRllqNSlwXea/6p+q4GX9IWt+b3AHa418Bn5LSZoO03Q+eTmWH35n8yPC+Q4juBXNz8r7c7CzRNswy/YMuvI3zOrJ/cicmZqWkT24OcGguID7z5Xjqtc5z+iCczjgMFcaUN5M86p2pjammFw7XNxb+uiUV0dzurPyUs4ZGZp3yPmvGFkdC6QtFSY+dwcB2nBoxzxC83t2kJHTOZZxUBxF2QNqKAYySMaxvlhtOZ2OUGmprXNz0j3AAUYyMlrGDYNZww93DvNc6IAdFout2NwCmVs2iVjvweDx07TxFaUXwTXsu59dfgkYNAX3Qfeu9XwvLouR/LX2OSjw90LsHUxpvaCQuStDZJA7m7oa3Eve4NYMQLzietiRQCpxWbHoV0hr7RFIcqMe4G9QkCpaGjBrjiR1SqjBvUntbtagk8Plz+D/AK738dOuh0emtKsntEkrGhoeS4YUAFcMNtM96qNKwCySJ1x9cMMes06g7v1H1CuHSZAwAUuLRtgu1aU6euiWnki7PYmyZiju03H73a+KzLXY3R4mjm9oZ+Lc0OS3PdrKB0jtTSaODHVsHXu4walxWl+q2fvzQaDSRZlUt7Lur4dnwVibSrXNoWV+q83lniApGKmadkzloYvEUYZIy04PW3S/tsShtskbr0Mj4z9VxFO7FS0lp20zUEkzzQ1F5xJqPrHHzoq0hByx7gg2iyyXbxjeAM3EYKkzhq0205QWq1ult9Vt1LXtRc29rGDx8HdxVjRGMlTkMVTsELzWSh5vqyOyAqQK7zUtNNqvWNt1hOsj54DipkrHdgarqTVST/Tdv6a3+vumX4bO60PcS4NY3F7y660agC7MY4ACpJB2FV9IaPEbOfs8rZo60cY3PIrscyRrXMJ1EhE0ixj7KIGVD4mtmcamj+cZeBI2CMDE5OdQdcqOhSIoo2PwbaX0ky/duqxpOy47m5AfrDetlFWseTWxVSpVdWTd/b+evArSvwwyIqO4tqFkLSnaW0Y4ULL0bhsLSajzp4LJqogrXOnH1fxFCXL4ChCSUKKzzrmgGRbDxKe7Fs8yqV5K+pHcuhsPZ8ypXIOz5n1VC+leQBeMUGw8StPRtrgj6I6JOLi69QjHNc+HIwtHRAIBpUZUNK1z14k5pSVzrweLlhqn4kUm+a/ljs2SVyN5EfUAE3qGtDqNDQ08Vx3OBhFx5F6tSWgZAUAz2o8Ftkri8nfgfis8jPpIf/SRtacGujT+PU6OTHou6uv0Qp3kuFHuaA0to3Xeph2ejTYstlrk1u7kPn39pLIx1O3cNNWtLw5barZr+b3WhrQtDdrv5nF3GqcmuJWQJn9pIzO7+PqnkZH9uYe1kn5GwHhNI6oo7ELDktLwKi73a1oMMhaJIpWgZ1c1oLSNp1EIy2Lh2rGunGCb4rTb6tGxflnLQSZCBRoc69QAZNvHAbgk2yy5UeN1CPjkufGnbeAXieSgNLwdhXdrVR2lbS7rSvP2kZTih2xGGkY2XJL7NHXixu1tp+dyHJZiMwOOPDNce61yHEyP+8fDIqUU7xiHOr3k8dyMhou3o31i/T9zo5ZgNp8kB9pwOpVmzXgHfkO2IFunLGEtNCKU761Ssd9THNU3UT0tf0ASwySzshlcWjUBiGhwrUanHfr20AViOzc1DI1vS6U2NKXrnNwjCuVZ38FPRVsjlNXXWloc5zHA3QaEmSEt6TTXExgitcNxiXFrbPJGxkj2EtB6Ja4yiRlHueQQ4Ag1xwGK6LcD4m+aV5eL1+5DRVp59jopamRjC6Nxxc5rSL8TtZLQXObgcRTC8SqM0Zvlo2q7YbC6O0MkEsFQ9rrola4ke+KNrmKo1rgZE+Qmt1ri0VzIaboHeaKXsmdNCWSUoXuvj5RWZBRRc8DLE7kWNjpMXdFupvqrkUbG5NKzPcw3Z06izSdl6lKOKR2QujzVS36Nmbj1xtbiR3tXQMLj1WhG5l9KlwH8uCDqq4TAxhllN34rfy29DjLHbXxOqw94ORXVaN0rHNUFpvUxjOLXbr3ZQ7VDFnIAabdap2jShpdjAaNwomcmFxNbCvLCd4cGvbh7PgPboXBjYW3WsGN0Elxcc3O+H/KFaW0Y0V1sHDpH/BSseRNak9b5KNtNLlcudbXuOB+KFuhuhGjg5uKteL/nz5FwQl9qtDg4Na1szSCaEg84Y2t/l5tpG9gBwKhYIZrQ6GaNjX3RCy4wtqHRyxYmMGt26Gi9SmGK0tNczZauaS51ovvBy5sysc5hdrJaXhopQNq52LqXc6kgtbLOLnVs0dSxpIJiaXPDiCWmhdkcg0HALVK2h81UlmdyGnLN/wB1OKYCV/ma081S+j2dkq7pK2h8skjR1pHEZdWtG/2gIQtb939volY0nLMkuCKvsDeweKj7A3sFXvaHnX8EjaX7fIJmdjnbqe6p3U4apEDoE9EUMT3EDsBoEeGCoLtmQ27fIpxGrNme5nUcAd4BGyhBFCEFQUb97bkVrRFgDl1q6qdVU3UGLTjXx9Ct43gA4va3X0WE0NajHEK3Hpguwf7HLX+JA2v3qNofFCTLrunm7jdrLcxjaKsBcAK11UoRrFc8fgistAcNm3ZXaFt2Kd9QIooakigjle0E6gGOe4UxyA1o+krPaHUMlgNQOs2HE68TcFU8pjmOebKCKg4DM6sd6o2u1Y0ae8rWtIfWvs72bhFQf4rOnjJN668H+XdTWiwr8ygZndo8StHQ1ra1xjlJ5uTB24nJ3yP4K1oyxWZwraZJI8aDoim4k0J4hdFo0aJiGbXu7Tr5I7hSgz2KJS8LM9DB0J5o1Yziuslt43XPYyrTyYaR+zcQdVclz0sTmOLXihbmCvS26TsJ6r67qP8ARVNJ+xT0DgTTAOa14d97M+KyjOS3TPSxeEwtRXpSjF9VZ+TduvmcGxwyI+St2SzveMAaDAmtGg7zkteXRFhFTem4CnmqwNmjJMbpSTruxVGronUaa1pm5M854KfhKL/1FGxyUJGo4jw/D4JaQY5zDdBIaau7ibo8yEznRt/dsd3vdXg1oAVzRlta14Y8kRyteyShILQaFrxTW1wa7XgDtQtWbVJSp4Z020+l9m1xS9LgdBRkMkbdbembda5+UbGOrJKRTAAgdKoxbhWlFp2h0hkc603ZmQxtkj6AHOt6oDTnzVZXuJ1iNUNPTvhfzQBYRdJNBdkDSDFcIJrEAMB4mpylZLYyaV4a1zWkBrWk1uxvEkcgaNWM5fTIXStTyCOi7RaZZWNiLgwyAdDAENF5wc4YkXQTiSt21xB8j60Lece4VG04LH5OxmztNpkFDdc2EHO8R0pabG4U30VG3aaLgGsJA1nWSdQ3JPaxtSmlNyZt2iaGLrEV2LMn0+MowBvpUrOsmkWx1/YxvcT1pAXU3BtaKT9OTnAODBsja1n+ACzynoPF08i7+vj3W/VuK8rrmWTpa051ePCg+CaPSc1audXCgBOA8AsmS0Pdi5xPeaoVVWU5JYlX0v6L2udHE29jK9tNlfmnfJAPeB8a/BY9n0VPJ1IZHV2MdTjRaDOSVsOJiuj6zmN8iaoymix8krKK82EbpCFpwJ8AfmqmlLc2SjWVoMakUNfz8VcbyQn95zB3En5K1Z+RzicZeDfxRYmpja1SGR6Ll/UHLZHW2NhjNZoxcMZIF9lSQ5lfeaSWlvZuUyK19Jwcy980lBK5oYxgNSwFjY3yup1SWtutFdZd31IuSxYcJiPs/irUfJ9mckryOyKN+Cu5yZTDjbtIRLg2rqrNZLEzDmXOP1iXeRNFejtdmbgxlz7PoEizkIbBI7qscd9KDiVaGgZtn9zV1HtcZ1t+76pueZu4JDPMxEpiBGCdqCLAxApCAo4BRGJDsCbZ1J8LgOjdrvVuIH8lWYMT+IogdjlZ7PLWrmurtArwoqz43DNpHeCvQIyBnTxVqKNpyoncnKeXojJC3qkjuNF6h9DtdiWMcPspn8nbNriaD9j8EXJyM80Nsk/iP+8fVN7XJ23/AHj6r0+PkrZDnHwp8irTOQthObT98j4FFx5GeUG2yHN7j3mvxS9sf2vIei9jj/RxYDk0n/6O9UWP9FthOYf3CUeiLiyM8Y9tfu4BMbW7dwXtf6q7BrEv9T8FH9WGj+zL/U/BFwys8VFoOwcERtpbrbwK9nH6M9HdiT+qn/Vro3sSf1kaFd5HjzbTFrvfnxVSaarqtwAyXt4/R3otuJicRvmf/pKsx8kdFM6tnj+0XO83FLYHme54/YtPi6I7RE2aNvVa4lrmV7EgxaK40xCk3SdkYb0dnJdQjpyOLRUUIutpXA7QvZ26NsTepZrP/Sj9EVssLOqyFvc1o+CrMGRnhlqktVqNRHI+92GOOGoANFA0VOA2o9l5F6QkyszwNrqM/wAiF7VJpYDWzj+KoTacbkS3zU5h/hnnFl/Rtaj+9fHH4lx8hTzWvZP0cwsoZpXP2houj4k+a6ObTjdRHmq0mnAcMOKLlKkiu3kxY4+rA0733nf5Eo8VnjZlFG3uYAqs+nN/mqsmmPzVK5agkbbpW0umg2YEeHcs20HHA03ZrKl0tqKqyaVxwOPei4WR0sD20F5ortq4eSFNbI2nBo+8T5UXPfS7tR8z6oE+kHHXxKaYSjY6H6TYM2N4/gqk1rYTgAO4lc/7Y/JQMxOaZBqPtO8cSoe07XDiVmF/f5pCbvTEXzOPyVXknxy80Ay96aoQK5GimAoUSKkYSichBonAQAQIrZDqNFXARmFA0WWOdt81I2kjWhNQ5GoKaLsekXDWERukTrNVlVTVSCxvxabLcqcVZbylcNnFcqU4YlcpRudhDynfu4q7DyhlOtcVZxuW1YGV/wCFLZ3YfDKb1Z0P05L2h5+iG7lDIPe8ysqQjf8AdIVSWUbPipudtXA04xvmRvDlA86x5qP047WfiseFwRCRiqOP8CHEvv087afAqtNp92/zWY6MalRtYU31KqYZZMyNh/KF/wCaqL9NkgVvcVzBO5Eld0RTetUeZI3hpQnf3/8ACgdJ7WjgFhQyFNXFA4nQe2N7I8lJlqZra07qA/JYTXqYekbJI2/aIv4bOA9EKaaKn7tngPRZpcgvkRqDSND9j2G+aTY4uyPP41WWZikJimZuxqCKI+4OJ9UnQQ9ng53qsw2gp/aj+QECb0NH2eA5Ndxd6qbbFBsd95ZQndtKNFaCqMy++wQnIOHjVQ+jo9V7iAgG0OSMz0BIMNFsr748Qfkl9GN7R/t9FDnXbU3OuTI0KZO4cU/gkkpZQvAJq7k6SQCru81MV/JTJIGgzBuHEpO7h4FJJBSBHuCi4nUAkkkaNCaDsRGgp0khxJMP5wV+yTkazwb6p0kjopyfELJNroa+Hqq8km7zHqnSQkayk2iDX/V8x6orZDsPl6pJK7GJFzzXLiR6qrNIDnTyTpLNrUpzeXcpPcNnwUHP3fBOkqRyzIB+wfBMXbvgkkmSSBP5onDzsTpIByYi/d8ENx3FJJMm5HwSDtySSZI9Qk9wGPFMkgLhm02fD1RWOGz88UkkwQxeE4lGz88UkkEtjGXv/Pio88NvkkkgR//ZZ" alt="" />
        </div>

      </div>
    </div>
  </div>
  </div>
  </div>
</template>

<script>
export default {
    name: "FeatureoneView",
}
</script>

<style>

</style>