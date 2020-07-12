<!--src/App.svelte-->
<script>
	import Navbar from "./Components/Navbar.svelte";
	import Banner from "./Components/Banner.svelte";
	import Services from "./Components/Services.svelte";
	import About from "./Components/About.svelte";
	import Testimonials from "./Components/Testimonials.svelte";
	import Social from "./Components/Social.svelte";
	import Footer from "./Components/Footer.svelte";
	import DATA from "./Data/data";
</script>

<!-- Navbar -->
<Navbar navlists={DATA.NAVBAR_DATA} header={DATA.HEADER} />
<!-- Banner -->
<Banner bannerData={DATA.BANNER_DATA} } />
<!-- Services -->
<Services serviceData={DATA.SERVICE_DATA} />
<!-- About -->
<About aboutData={DATA.ABOUT_DATA} />
<!-- Testimonials -->
<Testimonials testimonialData={DATA.TESTIMONIAL_DATA} />
<!-- Social Media -->
<Social socialData={DATA.SOCIAL_DATA} />
<!-- Footer -->
<Footer footerData={DATA.FOOTER_DATA} header={DATA.HEADER} />
