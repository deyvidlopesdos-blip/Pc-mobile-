      - name: Upload dos arquivos
        uses: actions/upload-artifact@v7.0.2
        with:
          name: arquivos-windows
          path: C:\Users\runneradmin\Desktop\
          if-no-files-found: warn
          retention-days: 1
