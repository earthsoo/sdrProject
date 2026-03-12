# sdrProject

## Install Radioconda

1. install here
   > https://github.com/radioconda/radioconda-installer/releases

2. install package and update
    ```
    :: 최신 패키지 리스트 업데이트
    conda update -n base -c conda-forge conda

    :: HackRF 제어 도구 및 GNU Radio용 소스 블록 설치
    conda install -c conda-forge hackrf gr-osmosdr
    ```

3. cheking
   ```
   #명령행 도구 확인
   hackrf_info

   #Run GNU Radio
   gnuradio-companion
   ```
