# Planted Society 
import Navigation from "@/components/Navigation";
import { Leaf, Target, Users, Globe } from "lucide-react";

const About = () => {
  return (
    <div className="min-h-screen bg-background">
      <Navigation />
      
      <main className="container mx-auto px-4 py-16">
        <section className="mb-16 text-center">
          <h1 className="text-5xl font-bold text-foreground mb-6">About Eat for Impact</h1>
          <p className="text-xl text-muted-foreground max-w-3xl mx-auto">
            What we eat matters. We're transforming food systems through plant-based initiatives.
          </p>
        </section>

        <section className="mb-16">
          <div className="prose prose-lg max-w-4xl mx-auto">
            <p className="text-lg text-muted-foreground leading-relaxed mb-6">
              That's why we work with cities to introduce more local food choices where plants are the star - Because food grown from the ground has a much lower environmental impact than most traditional animal-based ingredients. We connect plant-based brands with local restaurants to create lasting environmental change.
            </p>
            <p className="text-lg text-muted-foreground leading-relaxed mb-6">
              We are 100% plant-based and have worked with 10 cities both nationally and globally.
            </p>
            <div className="space-y-3 text-lg text-muted-foreground">
              <p className="font-semibold text-foreground">Through our initiatives, we:</p>
              <ul className="space-y-2 list-disc pl-6">
                <li>Reduce emissions that drive climate breakdown</li>
                <li>Protect water from overuse and pollution</li>
                <li>Preserve land and wildlife habitats</li>
                <li>Support biodiversity and protect ecosystems</li>
                <li>Improve air quality by cutting methane</li>
                <li>Create a more sustainable food system for future generations</li>
              </ul>
            </div>
          </div>
        </section>

        <section className="grid md:grid-cols-3 gap-8 mb-16">
          <div className="bg-card p-8 rounded-lg border border-border text-center">
            <div className="bg-primary/10 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
              <Target className="h-8 w-8 text-primary" />
            </div>
            <h3 className="text-xl font-semibold text-foreground mb-3">Our Mission</h3>
            <p className="text-muted-foreground">
              To transform food systems by connecting plant-based brands with local restaurants, 
              creating sustainable, delicious options that benefit people and planet.
            </p>
          </div>

          <div className="bg-card p-8 rounded-lg border border-border text-center">
            <div className="bg-primary/10 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
              <Users className="h-8 w-8 text-primary" />
            </div>
            <h3 className="text-xl font-semibold text-foreground mb-3">Our Approach</h3>
            <p className="text-muted-foreground">
              We work directly with cities, plant-based brands, and local restaurants to develop 
              sustainable food partnerships that make plant-based eating accessible and appealing.
            </p>
          </div>

          <div className="bg-card p-8 rounded-lg border border-border text-center">
            <div className="bg-primary/10 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
              <Globe className="h-8 w-8 text-primary" />
            </div>
            <h3 className="text-xl font-semibold text-foreground mb-3">Our Vision</h3>
            <p className="text-muted-foreground">
              A world where plant-based food is the norm, accessible in every community, and 
              recognized as essential for environmental and human health.
            </p>
          </div>
        </section>

        <section className="bg-primary/5 p-12 rounded-lg text-center">
          <Leaf className="h-16 w-16 text-primary mx-auto mb-6" />
          <h2 className="text-3xl font-bold text-foreground mb-4">Join Our Movement</h2>
          <p className="text-lg text-muted-foreground max-w-2xl mx-auto">
            Whether you're a city seeking sustainable food solutions, a plant-based brand looking to expand, 
            or a restaurant wanting to offer more sustainable options, there's a place for you in Eat for Impact.
          </p>
        </section>
      </main>
    </div>
  );
};

export default About;
