from http.server import BaseHTTPRequestHandler
import os

class handler(BaseHTTPRequestHandler):
    def do_GET(self):
        self.send_response(200)
        self.send_header('Content-type', 'text/html; charset=utf-8')
        self.end_headers()
        
        html = """
        <!DOCTYPE html>
        <html>
        <head>
            <title>Modelos ONU - Vercel Server</title>
            <style>
                body { font-family: sans-serif; text-align: center; padding-top: 50px; background: #f4f6f9; }
                .card { background: white; padding: 30px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); display: inline-block; }
                a { display: inline-block; margin: 10px; padding: 12px 20px; background: #1f77b4; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; }
                a:hover { background: #13527d; }
            </style>
        </head>
        <body>
            <div class="card">
                <h2>👑 Sistema de Gestión - Modelos ONU</h2>
                <p>Seleccione el panel al que desea ingresar:</p>
                <br>
                <a href="https://share.streamlit.io/" target="_blank">Portal de Escuelas</a>
                <a href="https://share.streamlit.io/" target="_blank">Panel de Secretaría</a>
            </div>
        </body>
        </html>
        """
        self.wfile.write(html.encode('utf-8'))
        return
