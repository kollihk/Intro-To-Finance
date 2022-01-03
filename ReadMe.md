# A Case Study: Beem It, A Digital Wallet

![Image](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBw0NDQ0NDQ8NDQ0NDQ0ODQ0NDQ8NDQ0NFREWFxURFRUYHSkhGBolGxUVIT0hKC0rLjAvFx8zRDMsNygtLisBCgoKDg0OFxAQFy0dHR0tLS0tLS0tLSsrKy0tLS0vKys3MC0tLSsrLSstKy0rKysrLSsrLSstLS0tKy0tKy0tLf/AABEIAJ0BQQMBIgACEQEDEQH/xAAbAAACAwEBAQAAAAAAAAAAAAABAgADBAYFB//EAD0QAAICAgECBAMGBAMGBwAAAAECAAMEERIFIQYTMUFRYXEUIjKBkaEHQnLBFiNSYoKSwtHwFSRTVFWxsv/EABoBAQEBAQEBAQAAAAAAAAAAAAIDAQAEBQb/xAA0EQACAgEDAgQDBQgDAAAAAAAAAQIRAwQhMRJBBRNRcTJhgRQikaGxM0JSYsHR8PFyguH/2gAMAwEAAhEDEQA/API1JqPBqfCSP31CyQ6kjSECSGSOhUCSGSJRHRJJJIqNoghkjSggCESSCNIYwhEAhESRtDCERRCJpw4jAxAYwM46hwYwMrBjgw0ZRaDGBlIMYGFoNFwMcGUgxwYGgNFwMdTKAZYDA0TaLw0cNKFMcGTaJyRoVpYrShWjKZJxJyRqVpYrTMrR1aSlEjKJrVparTGrS5WkJRJSiaVaWq8zK0dWkZRISibFaXK0xq0tVpGUSMomnnJKeUkl0k+k+W6k1H1F1Pvo/RpEi6jahjSEkJJGkjSEkLJGkjSELJGkjoRJJJIqFRIYIY0KgyQQzRBh3FEM2jRoQYohE6jBxGBi7kBnUZRYDGBlYMYGZRjRYDHBlQMYGBoDRaDHBlIMcGTaA0XAxwZSDLFMm4k2i4GOGlIMcNA4k3EvUyxWmZWlitJOJKSNCtLlaZVaWK0jKJKUTSrSxWmVWlqtJSiRcTWrSxWmZWjq0hKJKUTTzklPKGDpJ9J89k1DJqfXR90SSPBKISBBGi6jQySQwRo1EkkkjSGkCGaOm4hyL6aF7GyypN/AMwBP5Dv+U9LxV0VMC9KVtNxNSuxKheO2YAdvpKV3JvPCOWOJv70k2vZcniwSSTUi9EkkhmmkjQSTaNSGhBiRptHBEYRIZ1GFkIMrBjAwmFgMIMrBjAwhosBjgyoGMDA0BotBjgyoGMDA0FouBlimZwY4MDiScTQDHDTOGjBpJom0aVaOrTODHDSbRKSNKtLVaZQ0tVpGSJSiaQ0tVpkVparSUokZRNHOGUcpJPpB0nGak1G1BPoI+uhZI5g1KIaEhkhlEISSGSNDBJDJGhHQ+AMXzeo1N/LUrWH/AHV0P3YSnxtled1HJPqEcVD/AHAEP78p738MKApzMlvwpWig/I7Zv2VZ5HQum0dRvybMjIGPtmsALKGsLMSSOXbQ/vLJbI+P50IazNmn8OOMY8N7yd9vmznJJ2PVvAVyIbcS1chNb461YR/s8ezftOOYa+oJBHoQfhOqj6em1eHUxcsUrr8V9Of79gQz3/D3hPIzhzHGqn08xw2yfcKvv9ewnvnwFjNtEzQbf9JFZG/6QdxUQz+K6TDNwnPdc0m6964OBknq9e8PZGAwFoBRjpLV2Uc9+3yPyMx9NwLsq1aaULO3sOwA92J9h851Hshnxzx+apJx5u9jPJO6p8A11rvLy0rY+ycQv0257/oJj6x4Fvqra3GsGTWBviBqwr8Rrs02jxQ8Y0U59CyfVppfi1RyMIMGjvWu/pqdl0vwK7VC7MuGMGGwmhzH9RY6B+XedR6dVq8OmipZZVfHq/otzj4dzrereB7KqjdiWDJTWyAAXI92XXZvp/8AcfpfgZjULcy4Y6sAQnbmux25FuwPymdLPK/FtH5fmeYq473fpXP9PmckJBOq6x4Jemo34toyK1HJgAPMK+5GuzTk4Wj06fVYtRHqxStfmvdc/wCbFgMeoja8iQvIciBshd99Suej4f6S+deKUcV6R3LleQAHy2PciGhZpxxwc5ukluy7r6YSWKMF3sq8tSxbfazZ+IB9NT0W6DWnTBmu1gtfXBPu8DttD236d5RgeGmvzcjEW1dYwblaUJBZSBrjv4k+/tO26r4fbIwsfErsFYp8rkxQnmFrK+mxrudzei7dHwtVrceF4MSyvlOTd301e+3e+26pfX5iDGBlnU8M4uRZjsyuamALJ+FtqD/f0lAMg4+p9iMlOKlF2nv+JeDCGlAMcGTaC0Xq0cNKA0ZWk5RJNGlWjhpmDSxWk5InJGlWlqtMoaOrSLiRaNPKCV8pIOkNHNyahgnoR9FA1FjwSiGhYI8WUQhZNQySiGgQQyRoaO+6G32fw/k3ehu84A/N9VLOA+Ou2/hPoPhwDP6NkYKkebUTxBP+35lZ+mxr8pwV9D1s1disrISrKy6ZSPiJV8I+Z4a152pT+Prb/wCv7r9j1vC/XbcK9PvMaHdRdXv7hUnWwPYj13Pf8W9BRuqYoUcVznXzNdtMGHMj6r3+u5zPQOkWZmTXUoYqGV7G0eKIGGyT+2p13i3rNdfVcHRBGIytbr1XmRyH5J3/ADjXG5HVXHXReD9o4T6q9vuX8+qq78FHj/rD0mvAxj5VddSmzh93YOwKwR6AAb+exPC6B4XzMzVleq6t9rnJXevUqANk7+n1nsfxH6Wxtrza1L02IgZ17qrL+En5EEd/lPDbxLljGqxqT5FdahT5QKWOd9yx9e5+GppugWX7DjWjpOXxN+u92u74STvau252/XMnEx8FsPNyTk3cCBvi+Rz0eLcfbR9z+pnn+H+PTujW54VTffy4E+n4uKL9Njf5zjsro2WmOuXbW4pdgA7HTEnuCVPcA/Ezsej1/wDiPQ2xa9efR2Cb1tgea/qCREePNpcWHTpeZ1wllj5jVUvXZbLer54RxtaZfUcjSl77rNsdtsgbGz37Ko5D5T6D4a6PZ0tDZl5ipWfxVFh5HL48m/m7ewH5zhOk9Tv6bZd5aAXFGqJsRuVX3tn7vx+6PWNTR1DqlzaNt7rslnbSIPhs/dX6CYfS1+DLmi8cpxx4ElbpO/b92K+e3yvg93CqxMzrlb4oJpUm+0MgVTYoJJUH25cD7e8w+P8AqT3Z1lXJvKxyERd/d5gDk2vc7Ovynqfw0wmTIy7LBxNKeSwP8rlwT+nCcb1HK8++27/1bHf8mckftOJ6XFF61pO1hxxim995b371tsdT/DXMtGW1AJNT1Ozp/KrLrTD4fD85k8edSe7Osr5Hy6CERf5Q2gGP13v9J6f8LqdWZWQfRKwm/wCo8j+yCcf1DI82623e/Mtss3/U5b+85m4cUJ+J5ciW8IxV/OW9+9bWdV/DTMtGU9G2apqndlP4Q6ldMPh66nP+Iakqzcmuvsq32hQPQDlvX7zqP4YU6OXkt2VK1QH5b5N+yrOLyrmtte075WuznfzYn+8xi08erxDPKPCjBP5tq79+wm53H8M6fvZWQ34UrVAfqeTfsgnDHc7/AKC32boGXf6eb52j6fi1UP3hS7m+MqX2by1zOUYr6v8A8Ob6YTk9Sr3v/PyuT9z3Bfkd/luez/EfLP2ytASBXSuwD/MzMT+wWY/4dY4szw+u1Vdln0J0o/8A0Zg8WZPm9Qym3sCxkX6Jpf8AlmVSJySl4iorjHD85Ov0PN5RgZSDHBk2j6LLAY4aUgwgybQGaA0IaUhowaBomy8NHVpnDRw0m0SaNQaMrTOGjhpJxJSRo5SSjlJD0ho80iLHgImJnrQsUx4JRMohNSQwSiYhZI8GpRMaEkhh1KIRp6V1K7DsW2luLDsQe6svurD3E7EeLumZQDZ2GDaAByFVdoP0c6IE4OSVUmtjy6nQYdRJTmmpLunT/I7fP8a001mrpuOtHL1dq0TXzCL6n5mcTZYzszOSWYkszHZYn1JMWSKyml0WHTJ+Wqb5fLf1/wBI6fw94wfFr+z3r5+OOwU93RdfhG+xX5Gev/iToif5qYQ8wdwBjY66b5HloTgYIrZDL4Tpsk3OnFvnpbSfuuD3fEvie7PIXtXQDtalO9n2Zj7n9pg6N1W7CtFtLaOtMrbKuv8ApYf96mGQCaeyGkwwxeTGC6fT/P8AZ348V9KyVDZmGDaB3Y01W7+jb3r6zL1LxtVXWaenUDHH+tq0Tj81Ve2/mZxMk08UfBdKmm02lwnJuP4f3v5nS9E8Tri4mVUyO9+QbT53JdKSgUb33PfZ/Ocyff6w7gnHvxaaGKU5xW83b+n6ex0vRPEteJg5ON5TG2/zP8wMoVS1fEdvXtOb3sk/EwSCcdi08Mcpyit5u2dZ4U8VU4GO9NlL2my1rGZSgXjwVQuj/T+89P8Axr07/wBgP+HH/wCk4CTc48GXwjTZZvJJO5c7s7//ABt07/48f8OPMHiPxbVl4n2aig0qWVjspw4Ak6AX5kGcduTcwzH4Rpcc4zincXa3fK4Ok8IeIK+nm97KmtawKqlGVeIUkne/mR+k8F7SxLMdszEsfixOyZTuNuFnrjghDJPIl96dX9OBwYeUqBjbhGy0GENK+UIaFomy0GOGmflGDQNE2Xho4aZw0YNJtAZpDRw0zBowaTcSLNHKSVbkh6TKKjBqORBqeOLLoQiDUs1EIlUxIUiDUYwSqZRMWd10XBqbCw2bHw3S17BlXXsEdKw+uSvsHet/oJwxE15Oe1uPj45CBcc2FCoPI8iCd/pL45JXZ5dXgnmUIxdb7v5dMl6ru1W/O57mD4Zoyns8my8Kb7Upb7Mz0cV3xLWE67j4d5nx/DIsWmzzSKjVlWZD8QfINP4l9e+zrv29ZV07xLdj11IKqLPIseylrFfkhO9gaPfff9ZeOtJX0+6hLHa7KsZ3QIVSlSfvqGJ770v6ysXE881rYyajLZtJcPbdOXG1JqW9brp3tX5nROmLlWMjNdpU5DyMdr3P3vTQOl+pnqXeFq6nyhbeVqxkot5Cnm7JYSACN9iNTyuk9VfF84BEtS9BXaloYqwBJHoQfeaszxJdaL1KUqL6sep+KONJUSV49/mYoyVHoyx1csz6JVDb+G+Vb3XNdXNr37acvwqEOQtVpteqqi+pOPE3U2HW/XsQf7R38K0Vvb52SUqryK8UWLVzLZBQMRoHso3rfyMbpXiVRk/a72KtVjChKaqyVuUA6DMx+734mYMPxJdX5osSnJWy85PG9CwXI3+Ne/7R2iMVr3ab4S9FbdXTaram74+81ylWtPCtaC45N5qFOUMYlKzZyLKCGGz29RLKPBh55AeywpVkDHQ0UG52YgNzYA/dUBhueXd4hvsruRwh83JGUzAEN5gGgB31x9JpXxXcWvNtVFyX2C41OrlEtCheS6bfoB2mpjlDX1tLd/8AH+Xi169XPb02PG6jiNj320sQWqdkJX0OvcftOm8GdNp8l78mkXLdk04dYZeQQt3Zx8NbHf5TwMjqXmV21mrHBtvN3mLXqxdjXlqfZflLqfEOVVRVRQxpSok7qLI1hJ2S/wAYkejU4s+bAsa2bat3WyVt7W1ctq/oejX4YqC32ZF7VLTmtiALSLCx9m9e2+0c+DvvlFu5OmeuLYvHXGtl5C31+B9PiDMPUPE92QtitXUvm31XuUDKTYiBR/N7gCb8LxQFGdkuxGVlqFSiutlrQhdLdyJ9tt2+Xz7aeaf29R6ly+2zV/dS4V18TbbrZL3z+GcDHbqZobhfQv2hQzp91wqnTcfy3BZ4cpIxrar7bKMh2qZlxmNy2qCdBAe+xueT0fqb4dy31hWcK6gOCy/eXXeemPFlyNQ1VWPTXR5mqUrK1MXGmLDe+/7TSufFq1mcsUtulLdrdpT7NNp21TW38SaNdng5Rk4tQtdK8iq6wNZT5diGsElWr39Jo6L4ex/OxrEYZWPfTmAB6eBF1Q1+En4+n0nlf4rtD0OlOOgxVvWpFR+AW0feB2/eU9P8TXY6UVqtZGP9o4Fg2z5vZt6PtvtOIzw6+WPpct2muY/z+m9/s+H6lPXulDCNdRfnc1aPfWF0tLMOyBv5jNXhDFrtbN81Efh07KsQFeQV1KcWHzGz+spfxCz+V51FFzVYzY4e1DYxX+Vj37svfR+ZmPpPVHxGuZFDG7Hsx28zZ41uV2Rr37Cc0z1Shnnp5Ql8fra3d9q4VcJ+vqme/Z4SqFbayWN64H24VGkhSmu689+vtM+V4cqoxach7bSLVpctVjGyhEZgCvMHsygnsdb1qUHxReX58KtnAOB+F9eVr8X4vxSu3xJZ9mbGSqinzFRLWrR0axV9N99An3PqZivuRUdb1RuXdX8PHft27JJv9V6/WegYn2ynHoa9eWOjMlWM1z/h2CPvbPLvv2Goj+EAuSKTc4rOE+YHenToqkAoyb9e/wAZiHi+7mlhpxmcY5xrGNbBsiogDi5B+Xt84p8W3cgy1Y6hcSzDColgVaXIPu3qNCczzxxa+MYxUuItbuLt778e3N7cvY9fpHhzE8/HL2Pk0ZGNddSHqNZZl7NyAbtr1+crw+k4tuDxDa8zqteOuS1QForaoaUrvsNn03PGxfE19JxCi1/+TS2tAykh0cnkLO/f8tRqOvhktx2WnHx7slLuVdTOcVxx2awG79tdvmZjRs8Gr6m3Ntbd1tUpb0lu+lp0ud1TfB6p0T7JStlj7tbJvpWvjraVbU2737sB217zxwZ0XXvFCX5DOlaXVjFOKn2isEqT3Nyr/K5M5ncLR69LLM8aeZVJ7/j2rtXG/f2LQ0IaVcpA0LRVl4aENKg0gaBomzQGjBpnDRg0DQJGnlJKOckNANkGo+opE+RFiTFgMaAiWiyiYmoss1BqVTGmIRJDFlYsoiGLGklExCwQySiYrEkjRY0x2CSGCMQJJDBEmcCQwxYjQxZJIjiGKTJFmmBg3ITFJnGB3F3AYCZxlj7i7i7gJnBbH3DuVbk3OAyzlJylXKTlMoLLg0nKV8pOUNE2WhowaU8oQ0FAZcGjBpn5Rg0LRORfyklXKSZQT3CICIxEhE/OxkYmVESRiINS8ZDixYpEfUBErFlEyuQiMRFlYyGmKRAZZqJqVUilgimMZJRMViwGEwGUTGmLJJIZRMViwGEwRmkMUwmKYjSRTCYsRhIDITFM0yybimQxSZpjZCYCYSZWTNDYxMXchMUmcGxtxeUXcXc4Nj7k5SvlBynAbLeUnKVcpOUwDZbyh5SnlJymUBsvDQhpQGjcoGibZdzklPKSZRlnWkQERzAZ+SiySZWRARHIgMvGRVMrIkIjGLLRkNMQiQiNAZZMoLFjmCVixplZEBjmIZWLKIEUxjBLIVimCExTKJiTIYhhMBjQrFMBhMBjR1imAwmAxI6xSYphMUxGNgJikyGAzQtkJikyGKZoQExSZDEM0DYSYpMBMUzgNjbg5RTFJm0GyzlF5SvcG5jQGy3lJyle5NzKA2XcpOcp3ADMC2Xc5JVuSZQbP//Z)

## Overview

'beem_it' is a mobile payment app that lets people to split a payment of a single invoice. The app was built with a simple idea of peer-to-peer payments. The app is free to install and requires everyone who intends to use the features be registered with the app. 

Beem It was founded in 2017 by three big banks ( CBA, NAB and Westpac) and is backed by Australian payments provider, eftpos and by over a dozen Australian banks. Beem It was purchased by eftpos in 2020. [Mark Britt is appointed as a CEO of Beem It in 2021](https://www.eftposaustralia.com.au/news/new-beem-it-ceo-kicks-plan-national-aussie-rewards-program-0).


## Business Activities:

### Pay, request, transfer & split money instantly

The Beem It app allows split [payments](https://www.beemit.com.au/) for end users and/or receive payments by businesses instantaneously regardless of the bank.

### BPAY

[BPAY](https://www.beemit.com.au/bpay) integration with Beem It app helps consumers to schedule payments or split a bill.

### Gift Cards

Beem It allows users to send [giftcards](https://www.beemit.com.au/giftcards) to anyone with gift unwrapping experience to the recipients.

Beem It also has features to store loyalty cards and a range of stickers can be chosen with a payment.

### Groups

The app allows users to form a [group]((https://www.beemit.com.au/split-expenses)) to be able to split the bills otherwise, it is a hassle to manage a bill that needs to be shared among friends.

### Merchants and Businesses

The Beem It app also has features for businesses to integrate [Checkout API's](https://www.beemit.com.au/business/checkout) into their e-commerce sites to enable users to pay for products and services. Beem It integration enables the businesses to give their customers a seamless checkout experience eliminating the hassle of entering card details and thereby potentially reducing abandoned carts.

### Small Businesses

[Small businesses](https://www.beemit.com.au/business) that do not require e-commerce sites can accept payments through their phone with a Beem It app by linking their debit card. This enables them to receive payments instantaneously and eliminating manual payment processing.

### Rewards Program

Beem It has a loyal user base of over 1.5M. Businesses registering for the Rewards program gets access to its user base, insights, gamified social rewards, promotions supporting local businesses among other benefits.

#### Technology

Beem It uses EFTPOS system and works on Visa and Mastercard networks. Beem It requires QR code to receive payments while Osko can work with the POS systems directly. Beem It uses EFTPOS's ConnectID while Osko uses PayID to mask away BSB and account numbers.

## Landscape:

Beem It is a mobile [Digital Wallet](https://www.canstar.com.au/transaction-accounts/beem-it/) with lot more features than its competitors with split payments being the most popular one.

Osko is the closest domestic competetor with most of the features in common. However, its split payments, loyalty program and request money features may be of some interesting features to note.

In late 2021 EFTPOS, BPAY and NPPA had plans to amalgamate to work towards building next generation digital payments platform. The new platform is slated to use [Beem It's QR code system to replace POS systems](https://www.zdnet.com/article/accc-gives-green-light-to-eftpos-merger-with-bpay-and-nppa/). The new entity is called as Australian Payments Plus (AP+)

GPay and Apple Pay are the global bigtech competitors that offers similar features as Osko while using built-in NFC in their phones to store bank cards.

## Results

Although Beem It requires a separate app install unlike Osko which is integrated within the bank app, split payments and loyalty programs are of some interest to many loyal customers.

AP+ enables Beem It's features to get to the next level. AP+ has decided to use Beem It's QR code system to be used for payments processing nationally.

## Recommendations

Crypto currencies are widely accepted as financial assets and therefore, the next logical step for AP+ is to enable Beem It to evolve as a single digital wallet to link a consumers' bank and crypto addresses. This enables Beem It as an All-In-One wallet for consumers.

While industry standard QR code payment processing is a big blow to the BigTech's who control the built-in NFC chips, Crypto wallets would boost the usage of Beem It even further.