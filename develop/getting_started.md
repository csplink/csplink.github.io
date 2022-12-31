## quick start

1. Download and install [Visual Studio 2022 Community](https://visualstudio.microsoft.com/zh-hans/vs/)

   ![image-20220821184828961](assets/img/develop/image-20220821184828961.png)

2. After opening, select this installation

   ![image-20220821185308486](assets/img/develop/image-20220821185308486.png)

3. After the installation is complete, you can compile normally.

   ![image-20220821185653176](assets/img/develop/image-20220821185653176.png)

4. The ability to compile does not mean that it can run normally. The software requires the support of the database. The database path under `debug` is specified in `app.xaml.cs`, that is, under the same level path as `csp`

   - Database link: [csp_mcu_db](https://github.com/csplink/csp_mcu_db)

   - Chip package: [csp_hal_apm32f1](https://github.com/csplink/csp_hal_apm32f1)

   ![image-20220821185931551](assets/img/develop/image-20220821185931551.png)

   ![image-20220821190046606](assets/img/develop/image-20220821190046606.png)

5. From this, the software can run normally.

   ![image-20220821190417107](assets/img/develop/image-20220821190417107.png)

6. Since there is currently no stable version, please use the latest branch when compiling.

**Possible errors**

1. You can check if `nuget` is set correctly

   ![image-20220821191121598](assets/img/develop/image-20220821191121598.png)

2. If there is no item, please set it manually

   ![image-20220821191257245](assets/img/develop/image-20220821191257245.png)
