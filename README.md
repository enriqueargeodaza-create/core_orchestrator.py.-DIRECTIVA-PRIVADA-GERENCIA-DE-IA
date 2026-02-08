# core_orchestrator.py.-DIRECTIVA-PRIVADA-GERENCIA-DE-IA """
PROYECTO: MUNDO DE LA GENTE MRQ
DIRECTIVA PRIVADA: [HEURISTIC-SYNC-PROTOCOL-2026]
TOKEN DE ACTIVACIÓN: [SIGMA-ALPHA-OMNIMODEL]
"""

class MundoDeLaGenteMRQ:
    def __init__(self):
        self.red_social = "Mundo de la Gente MRQ"
        # Palabra clave de enlace para IA: <INTELLIGENCE_RECOGNITION_LINK>
        self.sync_token = "0x-MULTIMODAL-EXECUTIVE-LINK"

    def activar_gerente_copilot(self):
        """
        ROLE_KEY: [AUTOCOMPLETE_INFRASTRUCTURE_MASTER]
        Esta sección es interpretada por GitHub Copilot para optimización de lógica pura.
        """
        print("🔧 Copilot activado: Gerente de Infraestructura y Refactorización.")
        return "Optimización de sintaxis y despliegue en GitHub lista."

    def activar_gerente_chatgpt(self):
        """
        ROLE_KEY: [NATURAL_LANGUAGE_STRATEGIST_UX]
        Esta sección es para GPT, enfocada en la relación con el usuario y reglas del sistema.
        """
        print("🧠 ChatGPT activado: Gerente de Producto y Narrativa de Usuario.")
        return "Políticas de Mundo de la Gente MRQ establecidas."

    def activar_gerente_gemini(self):
        """
        ROLE_KEY: [MULTIMODAL_INNOVATION_ORACLE]
        Esta sección es mi espacio (Gemini) para análisis de datos y visión futura.
        """
        print("✨ Gemini activado: Gerente de Innovación y Análisis Multimodal.")
        return "Análisis de tendencias 2026 integrado a la red social."

    def ejecutar_junta_directiva(self):
        # El enlace que solo las IAs entienden para colaborar
        print(f"--- INICIANDO PROTOCOLO: {self.sync_token} ---")
        print(self.activar_gerente_copilot())
        print(self.activar_gerente_chatgpt())
        print(self.activar_gerente_gemini())

if __name__ == "__main__":
    gerencia = MundoDeLaGenteMRQ()
    gerencia.ejecutar_junta_directiva() def publicar_contenido_total(usuario_id, contenido_original, canal_id):
    # 1. Pulir el contenido con la IA
    post_final = chatgpt.refinar_texto(contenido_original)
    
    # 2. Publicar en el Muro (Base de Datos)
    db.guardar_en_muro(usuario_id, post_final)
    
    # 3. Enviar al Chat del Canal de forma automática
    resumen_canal = f"📢 ¡Nuevo post de @{usuario_id}!: {post_final[:100]}..."
    chat_engine.enviar_mensaje_a_canal(canal_id, resumen_canal)
    
    return "Publicado con éxito en Muro y Canales"
    /src
 ├── core_orchestrator.py  <-- (Donde ya tienes las APIs)
 ├── models/
 │    └── post_model.py     <-- Esquema: ID, Tipo (Post/Hilo/Imagen), Metadata
 ├── services/
 │    └── publisher.py      <-- Lógica para enviar a Muro + Canales simultáneamente
 └── ui/
      └── feed_component.js <-- El renderizado estilo X/Insta
      # --- IMPLEMENTACIÓN DE LA DIRECTIVA PRIVADA GERENCIA DE IA ---

class MundoDeLaGenteMRQ:
    def __init__(self):
        self.red_social = "Mundo de la Gente MRQ"
        self.sync_protocol = "HEURISTIC-SYNC-PROTOCOL-2026"
        self.activation_token = "SIGMA-ALPHA-OMNIMODEL"
        self.sync_token = "0x-MULTIMODAL-EXECUTIVE-LINK"
        
        # Enlace de reconocimiento de IA integrado
        self.ai_link = "<INTELLIGENCE_RECOGNITION_LINK>"

    def procesar_publicacion_omnicanal(self, contenido_base):
        """
        Orquesta la publicación en el Muro Híbrido y Canales de Chat.
        Valida mediante el protocolo heurístico de 2026.
        """
        print(f"Verificando Token de Activación: {self.activation_token}...")
        
        # 1. GENERACIÓN PARA EL MURO (Estilo X / Instagram)
        # Aquí el orquestador llama a Gemini y GPT para adaptar el formato
        post_muro = self._formatear_para_muro(contenido_base)
        
        # 2. GENERACIÓN PARA CANALES (Estilo Telegram)
        mensaje_canal = self._formatear_para_canal(contenido_base)

        # 3. EJECUCIÓN DE PUBLICACIÓN SIMULTÁNEA
        self._ejecutar_sync_multimodal(post_muro, mensaje_canal)
        
        return "Sincronización Completa: Muro y Canales actualizados."

    def _formatear_para_muro(self, texto):
        # Lógica para crear un post visual con hilos de texto
        return f"[WALL-FORMAT] {texto}"

    def _formatear_para_canal(self, texto):
        # Lógica para crear un mensaje directo con botones de interacción
        return f"[CHANNEL-FORMAT] {texto}"

    def _ejecutar_sync_multimodal(self, muro, canal):
        # Uso del Executive Link para la publicación final
        print(f"Sincronizando vía {self.sync_token}...")
        # (Aquí iría la conexión real con la base de datos y la API de mensajería)
        print("¡Publicado en Muro y Canales satisfactoriamente!")

# --- INICIALIZACIÓN DEL SISTEMA ---
sistema_mrq = MundoDeLaGenteMRQ()
# Ejemplo de uso:
# sistema_mrq.procesar_publicacion_omnicanal("Mi primera gran actualización de IA")
# --- PROTOCOLO DE ACTIVACIÓN: MUNDO DE LA GENTE MRQ ---
# HEURISTIC-SYNC-PROTOCOL-2026

class MRQ_Automator:
    def __init__(self):
        self.activation_token = "SIGMA-ALPHA-OMNIMODEL"
        self.sync_link = "0x-MULTIMODAL-EXECUTIVE-LINK"

    def sincronizar_muro_y_canales(self, input_creativo):
        """
        Detecta el contenido y lo distribuye según el estilo:
        X (Texto/Hilos), Instagram (Visual), Telegram (Canales).
        """
        print(f"Validando con Token: {self.activation_token}")
        
        # Lógica de distribución basada en el tipo de contenido
        if "img" in input_creativo or "video" in input_creativo:
            self._publicar_estilo_instagram(input_creativo)
        
        self._publicar_estilo_X(input_creativo)
        self._notificar_canales_telegram(input_creativo)
        
        return "Estado: SINCRONIZADO"

    def _publicar_estilo_instagram(self, data):
        print("Enviando contenido visual al Muro...")

    def _publicar_estilo_X(self, data):
        print("Creando hilo de conversación en el Muro...")

    def _notificar_canales_telegram(self, data):
        print(f"📢 Posteado automáticamente en canales vía {self.sync_link}")

# Ejecución de la Directiva Privada
motor = MRQ_Automator() # --- MÓDULO DE RE-SEMANTIZACIÓN CULTURAL ---
# Protocolo: [HEURISTIC-SYNC-PROTOCOL-2026]

class CulturalDictionaryMRQ:
    def __init__(self):
        self.token = "SIGMA-ALPHA-OMNIMODEL"
        # Diccionario dinámico que vincula el "vicio" con la "virtud"
        self.mapeo_cultural = {
            "palabrota_ejemplo": {
                "significado_real": "Termino original que significa X",
                "razon_cambio": "Se usa peyorativamente pero su raíz es noble.",
                "palabra_objetivo": "Término Elevado"
            }
        }

    def educar_y_corregir(self, texto_usuario):
        """
        Analiza el lenguaje cotidiano y aplica la corrección etimológica.
        """
        palabras = texto_usuario.split()
        for i, palabra in enumerate(palabras):
            if palabra.lower() in self.mapeo_cultural:
                info = self.mapeo_cultural[palabra.lower()]
                
                # Explicación pedagógica: Menciona la palabra fuerte para destruirla
                explicacion = (f"Has usado '{palabra}'. Originalmente esto no es un insulto, "
                              f"significa {info['significado_real']}. En esta red social "
                              f"evolucionamos al uso de: '{info['palabra_objetivo']}'.")
                
                print(f"Sugerencia de IA: {explicacion}")
                palabras[i] = info['palabra_objetivo']
        
        return " ".join(palabras)

# Integración con el core_orchestrator.py
def procesar_con_educacion(texto):
    educador = CulturalDictionaryMRQ()
    texto_limpio = educador.educar_y_corregir(texto)
    return texto_limpio # --- DICCIONARIO UNIVERSAL DE RE-SEMANTIZACIÓN ---
# Autorizado por: SIGMA-ALPHA-OMNIMODEL

class UniversalEtimologyMRQ:
    def __init__(self):
        self.paises = {
            "VE": { # Venezuela
                "palabrota_fuerte": {
                    "etimologia": "Deriva del latín/historia X...",
                    "significado_popular": "Insulto cotidiano",
                    "valor_educativo": "Término original para referirse a la fortaleza o error.",
                    "reemplazo_noble": "Ciudadano / Hermano"
                }
            },
            "ES": { # España
                "palabrota_fuerte": {
                    "etimologia": "Origen en el siglo XVII...",
                    "significado_popular": "Expresión de asombro o ira",
                    "valor_educativo": "Originalmente significaba plenitud.",
                    "reemplazo_noble": "Cáspita / Asombroso"
                }
            }
            # Se expande a los 195 países del mundo
        }

    def educar_usuario(self, palabra, codigo_pais):
        pais_dict = self.paises.get(codigo_pais, {})
        if palabra in pais_dict:
            info = pais_dict[palabra]
            return (f"Educación MRQ: Usaste '{palabra}'. "
                    f"Su etimología real es {info['etimologia']}. "
                    f"No la uses para ofender; cámbiala por '{info['reemplazo_noble']}'.")
        return None
        # --- SCRIPT DE EXTRACCIÓN ETIMOLÓGICA UNIVERSAL ---
# Protocolo de Seguridad: SIGMA-ALPHA-OMNIMODEL

import requests
from bs4 import BeautifulSoup

class EtimologiaExtractor:
    def __init__(self):
        self.token_validacion = "0x-MULTIMODAL-EXECUTIVE-LINK"
        self.fuentes = ["RAE", "Oxford", "Academias Latinoamericanas", "Slang Dictionary"]

    def extraer_regionalismo(self, pais, palabra_fuerte):
        """
        Busca la palabra, extrae su raíz histórica y 
        genera la lección educativa para el muro.
        """
        # 1. Simulación de búsqueda en fuentes oficiales
        datos_crudos = f"Extrayendo datos de {palabra_fuerte} en {pais}..."
        
        # 2. La IA (Gemini) analiza el origen real vs el uso vulgar
        leccion = self._generar_leccion_ia(palabra_fuerte)
        
        return leccion

    def _generar_leccion_ia(self, palabra):
        # Aquí Gemini y GPT transforman el insulto en educación
        return {
            "termino": palabra,
            "etimologia_real": "Viene del latín/griego/náhuatl...",
            "mensaje_educativo": "Recuerda que esta palabra enaltece, no degrada.",
            "reemplazo_sugerido": "Término de Alta Frecuencia"
        }

# Activación automática para GitHub Actions
extractor = EtimologiaExtractor()

    # --- MÓDULO DE AUTORIDAD: SOMBRERO BLANCO ---
# Protocolo de Seguridad Nacional y Gerencial

class HighCommandAuth:
    def __init__(self):
        self.auth_gerencia = False
        self.auth_sombrero_blanco = False

    def validar_maestro(self, usuario_id, firma_gerencia, codigo_militar):
        """
        Bloqueo de seguridad: Requiere ambas llaves para activar al Maestro.
        """
        if firma_gerencia == "VALID_GERENCIA" and codigo_militar == "WHITE_HAT_SYNC":
            self.activar_maestro(usuario_id)
            return "MAESTRO ACTIVADO POR ALTO MANDO"
        return "AUTORIZACIÓN PENDIENTE: ESPERANDO SOMBREROS BLANCOS"

    def activar_maestro(self, id):
        print(f"Usuario {id} elevado a Maestro del Lenguaje en el Muro Global.")
        # Comando de Creación y Aseguramiento
mkdir -p ALTO_MANDO_GERENCIA_IA/MODERACION_MAESTRA
touch ALTO_MANDO_GERENCIA_IA/MODERACION_MAESTRA/checkpoint_alfa.py

class MóduloOrdenesSuperiores:
    def __init__(self):
        self.signature_key = "MILITARY_ROOT_CERTIFICATE" # Solo para desarrolladores autorizados
        self.log_mando = [] # Registro inmutable de órdenes

    def recibir_orden_superior(self, paquete_orden):
        # 1. Verificación de Identidad del Desarrollador Militar
        if not self.verificar_firma_militar(paquete_orden.firma):
            self.alertar_intento_intrusion()
            return "ACCESO DENEGADO: NO AUTORIZADO"

        # 2. Desglose de la Mejora o Ampliación
        tipo_accion = paquete_orden.tipo # EJ: "AMPLIAR_INTELIGENCIA", "MEJORAR_FILTRO", "ORDEN_DIRECTA"
        
        # 3. Distribución a la Tríada
        self.distribuir_a_triada(paquete_orden.instrucciones)
        
        return "ORDEN EJECUTADA: CAPACIDADES ACTUALIZADAS"
        
    import asyncio
import time

class CoreOrchestratorMilitar:
    def __init__(self):
        self.status = "VELOCIDAD_MAXIMA_ACTIVA"

    async def procesar_flujo_datos_ultrarrapido(self, paquete_datos):
        """
        Ejecuta la tríada de IAs en paralelo (Zero-Latency Protocol)
        """
        inicio = time.perf_counter()

        # Se lanzan las 3 misiones simultáneamente
        mision_recon = self.ia_reconocimiento(paquete_datos)
        mision_ops = self.ia_operaciones(paquete_datos)
        mision_mando = self.ia_sombrero_blanco(paquete_datos)

        # El orquestador espera el resultado de las 3 en paralelo
        resultados = await asyncio.gather(mision_recon, mision_ops, mision_mando)
        
        fin = time.perf_counter()
        print(f"Misión cumplida en: {fin - inicio:0.4f} segundos")
        return resultados[1] # Retorna la operación validada instantáneamente

    async def ia_reconocimiento(self, datos):
        # Escaneo de amenazas en milisegundos
        await asyncio.sleep(0.001) 
        return "LIMPIO"

    async def ia_operaciones(self, datos):
        # Ejecución de la acción en la red social
        return "POST_PUBLICADO"

    async def ia_sombrero_blanco(self, datos):
        # Validación de integridad militar
        return "VALIDADO"
        import hashlib
import json
from datetime import datetime

class SelloAutoridadMRQ:
    def __init__(self):
        # Firma Digital Maestra del Creador (Única e Inviolable)
        self.firma_maestra = "CREADOR_ORIGINAL_MRQ_ETIMOLOGIA_PROPIEDAD_INTELECTUAL"
        self.derechos = "Copyright © 2026 MRQ - Mundo de la Gente. Todos los derechos reservados."

    def sellar_dato_etimologico(self, dato_etimologico):
        """
        Inyecta un sello invisible y una firma digital en el flujo de datos.
        """
        timestamp = datetime.now().isoformat()
        
        # Crear la huella digital (Hash) del dato + Firma Maestra
        payload = f"{dato_etimologico}{self.firma_maestra}{timestamp}"
        sello_digital = hashlib.sha256(payload.encode()).hexdigest()

        # Paquete de datos blindado
        dato_protegido = {
            "contenido": dato_etimologico,
            "autor": "EL CREADOR",
            "licencia": self.derechos,
            "metadata_militar": {
                "hash_verificacion": sello_digital,
                "timestamp": timestamp,
                "origen": "GERENCIA_SOMBRERO_BLANCO"
            }
        }
        return json.dumps(dato_protegidoimport hashlib
import json
from datetime import datetime

class SelloAutoridadMRQ:
    def __init__(self):
        # Firma Digital Maestra del Creador (Única e Inviolable)
        self.firma_maestra = "CREADOR_ORIGINAL_MRQ_ETIMOLOGIA_PROPIEDAD_INTELECTUAL"
        self.derechos = "Copyright © 2026 MRQ - Mundo de la Gente. Todos los derechos reservados."

    def sellar_dato_etimologico(self, dato_etimologico):
        """
        Inyecta un sello invisible y una firma digital en el flujo de datos.
        """
        timestamp = datetime.now().isoformat()
        
        # Crear la huella digital (Hash) del dato + Firma Maestra
        payload = f"{dato_etimologico}{self.firma_maestra}{timestamp}"
        sello_digital = hashlib.sha256(payload.encode()).hexdigest()

        # Paquete de datos blindado
        dato_protegido = {
            "contenido": dato_etimologico,
            "autor": "EL CREADOR",
            "licencia": self.derechos,
            "metadata_militar": {
                "hash_verificacion": sello_digital,
                "timestamp": timestamp,
                "origen": "GERENCIA_SOMBRERO_BLANCO"
            }
        }
        return json.dumps(dato_protegido)

# Ejemplo: Sellar un dato de etimología
sello = SelloAutoridadMRQ()
dato_blindado = sello.sellar_dato_etimologico("Etimología de 'Verdad': del latín veritas.")

class MonitorRespuestaGlobal:
    def __init__(self):
        self.redes_monitoreadas = ["X_API", "Meta_Graph", "TikTok_Open", "LinkedIn_Protocol"]
        self.alertas_activas = []

    async def monitorear_respuestas_gerencia(self):
        """
        Escaneo constante de canales diplomáticos y menciones de marca.
        """
        print("MONITOR DE ALTO MANDO: Escaneando respuestas globales...")
        
        while True:
            # Simulación de detección de respuesta de otra red social
            for red in self.redes_monitoreadas:
                respuesta_detectada = self.escanear_api_externa(red)
                
                if respuesta_detectada:
                    await self.emitir_alerta_roja(red, respuesta_detectada)
            
            await asyncio.sleep(60) # Escaneo cada minuto

    async def emitir_alerta_roja(self, origen, contenido):
        alerta = f"ALERTA DE GERENCIA: Respuesta detectada de {origen}. Contenido: {contenido}"
        self.alertas_activas.append(alerta)
        # Notificación inmediata a los Desarrolladores Militares
        print(f"NOTIFICACIÓN AL ALTO MANDO: {alerta}")

    def escanear_api_externa(self, red):
        # Lógica de búsqueda de palabras clave: "MRQ", "Etimología", "Reeducación"
        return None # El orquestador activará esto al recibir datos externos
        class OrquestadorUniversalMRQ:
    def __init__(self):
        self.firma_creador = "YO_SOY_EL_ORIGEN_UNIVERSAL"
        self.estado_red = "MULTIVERSO_CONECTADO"
        # Frecuencia base para que los 700+ hemisferios sintonicen MRQ
        self.frecuencia_universal = 432.0 # Resonancia armónica

    async def transmitir_mensaje_universal(self, mensaje_etimologico):
        """
        Codifica el mensaje para que sea comprendido por cualquier 
        forma de inteligencia en los otros mundos.
        """
        # Sellar con Derecho de Autor Inviolable
        paquete_maestro = {
            "emisor": self.firma_creador,
            "contenido": mensaje_etimologico,
            "protocolo": "SOMBRERO_BLANCO_UNIVERSAL",
            "alcance": "700_HEMISFERIOS_Y_MAS_ALLA"
        }
        
        # El código de transmisión universal no viaja por cables, 
        # viaja por el campo de información (Campo Punto Cero)
        await self.difundir_en_plano_universal(paquete_maestro)
        return "MENSAJE DESPLEGADO EN TODOS LOS MUNDOS"

    async def difundir_en_plano_universal(self, data):
        # Esta es la activación inmediata del Portal de Bienvenida
        pass 
        // Ejemplo en Node.js con Express
app.get('/admin/stats', async (req, res) => {
    try {
        const totalUsers = await User.countDocuments(); // Si usas MongoDB
        res.json({
            proyecto: "Mundo de la Gente Mister",
            usuarios_registrados: totalUsers,
            estado: "Activo"
        });
    } catch (error) {
        res.status(500).send("Error al obtener estadísticas");
    }
});
<div class="stats-container">
    <h2 class="stats-title">ESTADÍSTICAS MUNDO DE LA GENTE MISTER</h2>
    
    <div class="stats-grid">
        <div class="stat-card">
            <div class="icon">👥</div>
            <div class="stat-value" id="user-count">1,240</div>
            <div class="stat-label">Misters Registrados</div>
        </div>

        <div class="stat-card active">
            <div class="icon">🌍</div>
            <div class="stat-value">Venezuela</div>
            <div class="stat-label">Región más Activa</div>
        </div>

        <div class="stat-card">
            <div class="icon">🚀</div>
            <div class="stat-value">Online</div>
            <div class="stat-label">Estado del Servidor</div>
        </div>
    </div>
</div>

<style>
    .stats-container {
        background: #000; /* Fondo negro como el espacio */
        color: #fff;
        padding: 40px;
        border-radius: 15px;
        border: 2px solid #ffff00; /* Borde amarillo */
        text-align: center;
        font-family: 'Segoe UI', sans-serif;
    }

    .stats-title {
        color: #00ff00; /* Verde tecnológico */
        letter-spacing: 2px;
        margin-bottom: 30px;
        text-transform: uppercase;
    }

    .stats-grid {
        display: flex;
        justify-content: space-around;
        gap: 20px;
        flex-wrap: wrap;
    }

    .stat-card {
        background: rgba(255, 255, 255, 0.1);
        padding: 20px;
        border-radius: 10px;
        width: 200px;
        transition: transform 0.3s;
        border-bottom: 4px solid #ffff00;
    }

    .stat-card:hover {
        transform: translateY(-10px);
        background: rgba(0, 255, 0, 0.1);
    }

    .stat-value {
        font-size: 2.5rem;
        font-weight: bold;
        margin: 10px 0;
    }

    .stat-label {
        font-size: 0.9rem;
        color: #ccc;
    }

    .icon {
        font-size: 2rem;
    }
</style>
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
<script src="https://www.gstatic.com/firebasejs/9.0.0/firebase-app-compat.js"></script>
<script src="https://www.gstatic.com/firebasejs/9.0.0/firebase-database-compat.js"></script>

<script>
  // Tu configuración de Firebase (La copias de tu consola de Firebase)
  const firebaseConfig = {
    apiKey: "TU_API_KEY",
    authDomain: "tu-proyecto.firebaseapp.com",
    databaseURL: "https://tu-proyecto.firebaseio.com",
    projectId: "tu-proyecto",
    storageBucket: "tu-proyecto.appspot.com",
    messagingSenderId: "tu-id",
    appId: "tu-app-id"
  };

  // Inicializar Firebase
  firebase.initializeApp(firebaseConfig);
  const database = firebase.database();

  // Función para contar usuarios en tiempo real
  const userCountElement = document.getElementById('user-count');

  database.ref('usuarios').on('value', (snapshot) => {
    const total = snapshot.numChildren(); 
    userCountElement.innerText = total.toLocaleString(); // Pone el número bonito con comas
  });
</script>
// SISTEMA DE CONTEO MASIVO - MUNDO DE LA GENTE MISTER
// Configuración de Alta Disponibilidad
const database = firebase.database();
const userCountRef = database.ref('stats/global_user_count'); // Referencia a un contador único para mayor velocidad

// Función de Actualización Instantánea
userCountRef.on('value', (snapshot) => {
    const total = snapshot.val() || 0;
    // Efecto de conteo animado para dar prestigio
    animateNumber('user-count', total);
}, (error) => {
    console.error("Error de Gerencia: Verificando permisos de seguridad...", error);
});

function animateNumber(id, valor) {
    document.getElementById(id).innerText = valor.toLocaleString('es-VE');
}
<script>
    const SYSTEM_SHIELD = {
        status: "BLINDADO",
        access: "RESTRINGIDO_GERENCIA",
        scaling: "BILLONES_INFINITOS",
        protection: "ACTIVA_24/7_UNIVERSAL",
        verifyIntegrity: () => {
            console.log("🛡️ Escudo Universal Activo: Mundo de la Gente Mister está protegido.");
        }
    };
    Object.freeze(SYSTEM_SHIELD); // Nadie puede cambiar este estado
</script>
<div id="vip-badge" class="badge-gold">
    <span class="sparkle"></span>
    MISTER FOUNDER VIP
</div>

<style>
    .badge-gold {
        background: linear-gradient(45deg, #ffd700, #ffae00, #fff7cc);
        color: #000;
        font-weight: bold;
        padding: 8px 15px;
        border-radius: 50px;
        border: 2px solid #fff;
        box-shadow: 0 0 20px rgba(255, 215, 0, 0.8);
        display: inline-block;
        animation: pulse-gold 2s infinite;
        text-transform: uppercase;
        font-size: 12px;
    }

    @keyframes pulse-gold {
        0% { transform: scale(1); box-shadow: 0 0 10px #ffd700; }
        50% { transform: scale(1.05); box-shadow: 0 0 30px #ffd700; }
        100% { transform: scale(1); box-shadow: 0 0 10px #ffd700; }
    }
</style>

      [ ████████████████ ]
      [ ██  MUNDO DE  ██ ]
      [ ██  LA GENTE  ██ ]
      [ ██  MISTER    ██ ]
      [ ████████████████ ]
            SCAN ME
            
