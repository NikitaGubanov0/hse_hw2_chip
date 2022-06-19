# hse_hw2_chip

# [Colab](https://colab.research.google.com/drive/1l5Xg17Y7BfFV10DjDxE8IXkPFBOIwl7L)
## Анализ FastQC
Изначально я посмотрела анализ неподрезанных чтений, там было все достаточно печально. Для всех образцов per base sequence quality было в красной зоне, поэтому прилось подрезать все файлы.

## Было для ENCFF838NYU

![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157700286-a33a0aac-7c43-475c-a09f-04162c40812e.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157700210-8ad2c337-6cf7-4fbe-8c50-ef61936aa7a4.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157700345-85385926-f3ce-4ba3-97fb-4367b480883d.png)

## Стало

![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157700447-754a86cd-ab33-49bd-b9e3-a0fe7729d8fc.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157703593-0f26e5d4-2860-40cd-abd1-d40f73ec0033.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157704231-ac474ca9-f537-495f-be4c-e147b6c193bc.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157704347-0d9dada1-d677-4d2d-8363-2107da55f0c3.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157704469-5ae39fdf-6e1a-490e-bab7-303835c85861.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157704629-ec87154f-e66b-4d38-9016-4b33ff3cb180.png)

## Было для ENCFF061JXC

![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157707092-6aaee43a-bb43-4006-a60e-6c12521eb5e4.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157707233-04be777a-5b19-4b17-bce3-4261407e5f9d.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157707672-65fc80a7-df0f-4066-a036-4f9f94901562.png)

## Стло

![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157707832-468fa5db-238a-4496-b715-d08834bbef5e.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157707989-5bd752d3-c0c3-4691-bde1-8030f27794ab.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157708687-475cc60e-d0fb-43ba-8327-1a7535431bb1.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157709151-530ecb5f-6129-44e1-9888-3f10aeca5473.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157709228-c56e9473-65a9-454c-bc8d-d88b5d76548c.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157710974-2c47a8da-d9e9-4485-9a58-c96fec44e531.png)


## Было для ENCFF684TXQ

![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157714201-434d7cb9-637f-4e82-9563-89ff3e09a0c1.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157714256-27b11e27-c2b8-4ab1-b988-a239c4ea9c1a.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157714309-e79c2ad5-913b-48ac-89e5-b3d69b9b5b3e.png)


## Стало
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157711380-82dcbf53-de0b-4801-8b8d-0d8c903a79c7.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157711452-57d3b23c-51db-46f7-a1dc-6999487b8518.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157711563-7fe085db-04e2-425f-91c1-17ec673c9a75.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157711736-01c93eff-5100-420b-aba3-7e29863c3bf1.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157714593-c49c2e6a-fcc0-418d-a694-9c89ead516b1.png)
![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157714716-333ba73b-cb18-4726-969c-71492a8af869.png)


Можно увидеть, что качество прочтений стало намного лучше, почти всё в зеленой зоне или немного в желтой. GC состав не всегда хороший, но близок к идеалу.

![](https://github.com/NikitaGubanov0/hse_hw2_chip/blob/main/image/157717804-9d666215-2cdc-4de8-8310-3f5d73aefdd8.png)

Мы выравнивали риды на одну хромосому, может быть именно поэтому не такой большой процент выравниваний получился.

## Диаграммы находятся в папке diagr
По диаграммам видно, что в каких-то случаях пересечений получилось много, в каких-то довольно мало. В принципе, мы выравнивали на одну хромосому, а в encode выравнивание для всех хромосом. Понятно, что пересечение encode с файлом и файла с encode получилось разное, поскольку пересечение считается как число таких участков в первом файле, которые встречаются и во втором.
