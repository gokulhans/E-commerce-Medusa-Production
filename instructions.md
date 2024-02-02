psql "postgres://default:KoSBl0T1AYUu@ep-still-field-51970156.us-east-1.postgres.vercel-storage.com:5432/verceldb?sslmode=require"


npx create-medusa-app@latest --seed --db-url postgres://default:KoSBl0T1AYUu@ep-still-field-51970156.us-east-1.postgres.vercel-storage.com:5432/verceldb?sslmode=require

                                                                           │
                                 │   Change to the `medusa-backend` directory to explore your Medusa project.   │
                                 │                                                                              │
                                 │           Start your Medusa app again with the following command:            │
                                 │                                                                              │
                                 │                       npx @medusajs/medusa-cli develop   



https://govindhansv-medusaecomm-f189by373ww.ws-us107.gitpod.io/

npx medusa user -e some@email.com -p some-password
npx medusa user -e admin@gmail.com -p admin 

// for storefront
mv .env.template .env.local


in accordion.tsx file remove unneccessery commands

{/* @ts-expect-error */}

line 59 

   {/* <AccordionPrimitive.Header className="px-1">
        <div className="flex flex-col">
          <div className="flex w-full items-center justify-between">
            <div className="flex items-center gap-4">
              <Text className="text-ui-fg-subtle text-sm">{title}</Text>
            </div>
            <AccordionPrimitive.Trigger>
              {customTrigger || <MorphingTrigger />}
            </AccordionPrimitive.Trigger>
          </div>
          {subtitle && (
            <Text as="span" size="small" className="mt-1">
              {subtitle}
            </Text>
          )}
        </div>
      </AccordionPrimitive.Header> */}


      Accodion Commented

29 index 
       {/* <Accordion type="multiple">
        {tabs.map((tab, i) => (
          <Accordion.Item
            key={i}
            title={tab.label}
            headingSize="medium"
            value={tab.label}
          >
            {tab.component}
          </Accordion.Item>
        ))}
      </Accordion> */}


// import Accordion from "./accordion"

moved accordion file producyt tab folder
