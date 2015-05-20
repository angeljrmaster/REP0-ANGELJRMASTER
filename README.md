# REP0-ANGELJRMASTER
REP0-angeljrmaster
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<addons>
<addon id="plugin.audio.sonora"
       name="Sonora"
       version="1.0.5"
       provider-name="angeljrmaster">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
    <import addon="script.module.simplejson" version="2.0.10" />
    <import addon="script.common.plugin.cache" version="2.5.1" />
    <import addon="script.module.parsedom" version="2.5.1" />
    <import addon="script.module.simple.downloader" version="1.9.4" />
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides>audio</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">Sonora</summary>
    <description lang="en">Terra's Sonora is a online service to listen more that 20 millons of songs and radios for free. With one free account you can create playlist, mark songs as favorites and download songs (premium service). With this plugin you can listen the sonora library without ads. Its only for educational porpouses.</description>
    <description lang="es">Sonora de Terra es un servicio online para escuchar más de 20 millones de canciones y radios gratuitamente. Con una cuenta gratuita usted puede crear playlist, marcar canciones como favoritas y descargar canciones (servicio premium). Con este plugin ustede puede escuchar toda la biblioteca multimedia sin publicidad. Este addon es solo para propósitos educativos.</description>
    <description lang="pt">Sonora Terra é um serviço online para ouvir mais de 20 Milhões de músicas e rádios de graça. Com uma conta gratuita você pode criar playlist, músicas marcar como favoritos e download de músicas (serviço premium). Com este plugin, você pode ouvir a biblioteca sonora, sem anúncios. Seu somente para porpouses educacionais.</description>
  </extension>
</addon>
<addon id="repo.angeljrmaster" name="angeljrmaster" version="1.0.1" provider-name="angeljrmaster">
	<extension point="xbmc.addon.repository" name="angeljrmaster">
		<info compressed="false">https://github.com/angeljrmaster/angeljrmaster/raw/master/addons.xml</info>
		<checksum>https://github.com/angeljrmaster/angeljrmaster/raw/master/addons.xml.md5</checksum>
		<datadir zip="true">https://github.com/angeljrmaster/angeljrmaster/raw/master/repo/</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>Install angeljrmaster Addons</summary>
		<description>Download and install addons by angeljrmaster</description>
		<platform>all</platform>
	</extension>
</addon>
<addon id="plugin.video.colombiatv"
       name="ColombiaTV"
       version="1.0.5"
       provider-name="angeljrmaster">
  <requires>
    <import addon="xbmc.python" version="2.1.0" />
    <import addon="script.module.simplejson" version="2.0.10" />
    <import addon="script.common.plugin.cache" version="2.5.1" />
    <import addon="script.module.parsedom" version="2.5.1" />
    <import addon="script.module.simple.downloader" version="1.9.4" />
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides>video</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <platform>all</platform>
    <summary lang="en">ColombiaTV</summary>
    <description lang="en">ColombiaTV is a hub for the principal TV Channels from Colombia</description>
    <description lang="es">ColombiaTV centraliza los principales canales de Televisión de Colombia</description>
  </extension>
</addon>
</addons>
