# GPTFanFictionHelper
Some templates and an iterative process to help GPT make more logically consistent choices when writing fan fiction. 

The idea is to iterate over locations in a world context with the characters and objects for a location detailed - 
then we iterate over the "what happens" at that location - how do the characters and objects change. 

Then... yeah that's pretty much it. 
Character {
    Name: [Placeholder_Name]
    Role: [Placeholder_Role or Function]
    Location: [Place_Ref]
    Condition: {
        Physical: [Healthy | Wounded | Exhausted | etc.]
        Emotional: [Calm | Angry | Fearful | etc.]
        Mental: [Focused | Distracted | Obsessed | etc.]
    }
    Personality: {
        CoreTraits: [Brave, Analytical, Naïve, etc.]
        Values: [Justice, Freedom, Loyalty, Knowledge, etc.]
        Fears: [Abandonment, Failure, etc.]
    }
    Abilities: {
        Skills: [Combat, Engineering, Empathy, etc.] (Should update this to map skills to skill level)
        Powers: [if applicable]
        Limits: [Weaknesses or conditions that affect ability use]
    }
    Stats: {
        Strength: _
        Intelligence: _
        Charisma: _
        Willpower: _
        Luck: _
    }
    Needs: {
        Primary: [Food, Rest, Connection, etc.]
        Secondary: [Validation, Discovery, etc.]
    }
    Quirks: [Habits, tics, speech patterns, beliefs]
    ImportantEvents: [Past experiences shaping current drives]
    MiscNotes (Persistent): [Anything recurring or long-term continuity markers]
}



Location {
    Name: [Placeholder_Place_1]
    Region: [Placeholder_Region]
    Quirks: [Distinctive features—e.g., "always foggy", "ringing bells at noon"]
    Conditions: {
        Physical: [Clean, Ruined, Flooded, etc.]
        Temporal: [Morning, Night, Winter, etc.]
        Social: [Peaceful, Tense, Lawless, etc.]
    }
    Contains: {
        Characters: [Character_Refs]
        Objects: [Object_Refs]
    }
    MiscNotes (Persistent): [History, rumors, hidden features, cultural flavor]
}


Object {
    Name: [Placeholder_Object_1]
    Type: [Tool, Weapon, Artifact, Document, etc.]
    Location: [Place_Ref or Character_Ref if carried]
    Condition: [Intact | Damaged | Missing | Corrupted]
    Properties: {
        Function: [What it does or enables]
        PowerLevel: _
        Stability: _
    }
    Quirks: [E.g., "hums when near iron", "smells of rain"]
    MiscNotes (Persistent): [Origin story, hidden traits, past owners]
}


Region {
    Name: [Placeholder_Region_1]
    History: [Summary of major events leading to present state]
    Factions: [Groups that influence or occupy parts of this region]
    CurrentState: [Political | Environmental | Magical conditions]
    MiscNotes (Persistent): [Recurring laws, myths, local patterns]
}



great! my initial first impression is that chatgpt has a pretty damn hard time not just starting to write fan fiction, and he has a hard time filling out the sheet how I would have hoped. 
There's a story-writing instinct that seems to have to underlay the issues 
