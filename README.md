# spring
# List of frequently used annotations in Spring Boot apps 

<table>
<tbody>
  <tr>
    <td colspan="2">Core Spring</td>
  </tr>
  <tr>
    <td>Bean</td>
    <td>@Bean</td>
  </tr>
  <tr>
    <td>stereotype</td>
    <td>@Component, @Controller, @RestController, @Configuration, @Service, @Repository</td>
  </tr>
  <tr>
    <td>Bean State</td>
    <td>@PostConstruct, @PreDestroy</td>
  </tr>
  <tr>
    <td>Configuration</td>
    <td>@Import, @PropertySource, @Value, @ComponentScan</td>
  </tr>
  <tr>
    <td>Bean Properties</td>
    <td>@Lazy, @Profile, @Scope, @DependsOn, @Order, @Primary, @Conditional, @ConditionalOnBean, @ConditionalOnMissingBean, @ConditionalOnClass, @ConditionalOnMissingClass, @ConditionalOnProperty, @ConditionalOnMissingProperty</td>
  </tr>
  <tr>
    <td>Bean Injection</td>
    <td>@Autowired, @Qualifier</td>
  </tr>
  <tr>
    <td>Validation</td>
    <td>@Valid, @Validated, @NotNull, @NotEmpty, @NotBlank, @Digits, @Past, @Future</td>
  </tr>
  <tr>
    <td colspan="2">Spring Boot</td>
  </tr>
  <tr>
    <td>Application</td>
    <td>@SpringBootConfiguration, @EnableAutoConfiguration, @ConfigurationProperties, @ConstructorBinding, @ConfigurationPropertiesScan, @SpringBootApplication, @EntityScan, @EnableJpaRepositories</td>
  </tr>
  <tr>
    <td>Spring Boot Tests</td>
    <td>@SpringBootTest, @WebMvcTest, @DataJpaTest, @JsonTest, @MockBean, @SpyBean, @Mock</td>
  </tr>
  <tr>
    <td>Spring Test</td>
    <td>@ContextConfiguration, @ExtendWith, @SpringJUnitConfig, @TestPropertySource, @DirtiesContext, @ActiveProfiles, @Sql</td>
  </tr>
  <tr>
    <td>Transactions</td>
    <td>@EnableTransactionManagement, @Transactional</td>
  </tr>
  <tr>
    <td>JPA</td>
    <td>@Id, @GeneratedValue, @Entity, @Column, @Table, @PersistenceContext, @Embedded, @Embeddable, @EmbeddedId, @AttributeOverride, @Transient, @CreationTimestamp, @UpdateTimestamp, @ManyToOne, @JoinColumn, @OneToOne, @MapsId, @ManyToMany, @JoinTable, @BatchSize, @FetchMode</td>
  </tr>
  <tr>
    <td>Spring Security</td>
    <td>@EnableWebSecurity, @EnableGlobalMethodSecurity, @PreAuthorize, @PostAuthorize, @RolesAllowed, @Secured</td>
  </tr>
  <tr>
    <td>AOP</td>
    <td>@EnableAspectJAutoProxy, @Aspect, @Before, @AfterReturning, @AfterThrowing, @After, @Around, @Pointcut</td>
  </tr>
</tbody>
</table>
